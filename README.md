# projeto-rainha-store
um site que automatiza emails de suporte pra contas de streaming, e serviços, usando python pra back end, e typescript/javascript pra front-end

como sao muitos emails, o site agora guarda as credenciais em um arquivo, chamando a função pesquisar_emails() para extrair e retornar o email e senha alvo do cliente, assim evitando loops desnecessários, após pegar o email e senha alvo, o código realiza o login, extrai as ultimas 5 mensagens mais recentes da caixa de entrada, extraindo assunto, remetente, e desinatário.

após isso criei as funções pra extrair as mensagens do email equivalente a o site alvo que o cliente deseja receber o código, que extraem os códigos direto do html, usando regex, e verificações pra ver se o email da mensagem, e remetente batem com o que o cliente preencheu