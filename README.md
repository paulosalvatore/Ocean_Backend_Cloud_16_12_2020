# Instruções para subir os projetos na nuvem

1. Fazer o login no GitHub
2. Fazer um fork desse projeto
3. Fazer o login no Heroku (https://id.heroku.com/login)
4. Na tela inicial do Heroku, clique no botão `Create new app`, ou vá pelo botão `New > Create New App`
5. Digite o nome do app e clique em `Create app`
  OBS.: O nome precisa ser único
6. Na sessão `Deployment method`, clique em `GitHub Connect to GitHub`
7. Desce um pouco a página e clique no botão `Connect to GitHub`
8. Na janela que abriu, autorize a aplicação do Heroku na sua conta do GitHub
9. Com as contas conectadas, procure por `Search for a repository to connect to`
10. Digite o nome do repositório e clique em `Search`
11. Selecione o repositório que deseja subir no Heroku e clique em `Connect`
12. Na sessão `Automatic deploys`, clique no botão `Enable Automatic Deploys`
  Isso fará com que todo commit feito na branch `main` inicie automaticamente uma build do projeto no Heroku
13. Para testar se o build está funcionando, precisamos fazer um deploy manual de início. Na sessão `Manual deploy`, clique no botão `Deploy Branch`
14. Clique no botão `View`, isso irá abrir uma aba do navegador com o seu app
  Note que ele fica carregando infitamente, isso significa que tem um erro na nossa aplicação. Logo depois de um tempo, a mensagem `Application error` aparece

