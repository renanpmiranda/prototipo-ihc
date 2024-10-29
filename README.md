Projeto EcoCheck

Link do deploy: https://prototipo-ihc-ctz6.vercel.app/index.html

Integrantes do grupo:
Lucas Farias da Silva – RA 10402521
Nathalia Teixeira – RA 10395853
Renan Pires de Miranda – RA 10402446

- Descrição:
O EcoCheck é uma aplicação web focada em alertar os usuários sobre desinformações relacionadas a temas ambientais. A plataforma permite o cadastro de usuários, a visualização de notícias verificadas, e a gestão de notificações, além de integrar redes sociais e funcionalidades de recuperação de senha.

- Estrutura dos Arquivos:

index.html: Página principal do login, onde os usuários podem entrar com suas credenciais ou acessar redes sociais para autenticação. Também oferece links para a recuperação de senha e cadastro de novos usuários​(index).

cadastro.html: Página de cadastro de novos usuários. Nesta página, os usuários podem criar uma nova conta fornecendo informações básicas como nome, e-mail e senha​(cadastro).

recuperacao_senha.html: Página de recuperação de senha. Permite que os usuários insiram seus e-mails para receber um link de redefinição de senha​(recuperacao_senha).

home.html: Página inicial da aplicação após o login. Contém links para acessar várias funcionalidades, como perfil de usuário, notificações, feed de notícias, e página de itens salvos​(home).

minha_conta.html: Página do perfil do usuário. Exibe informações básicas do usuário, redes sociais vinculadas e oferece opções de acesso à configuração da conta​(minha_conta).

config.html: Página de configurações onde o usuário pode ajustar preferências como idioma, notificações, verificação automática de dados e tema do aplicativo​(config).

alert.html: Página de alerta que exibe notificações relacionadas a desinformações ambientais detectadas pela plataforma, com a possibilidade de compartilhar ou visualizar direções​(alert).

feed.html: Página de feed de notícias, onde o usuário pode visualizar uma lista de notícias verificadas e pesquisar por palavras-chave. A página também permite salvar notícias para posterior consulta​(feed).

pagina_salvos.html: Página onde o usuário pode visualizar as notícias que salvou anteriormente no feed​(pagina_salvos).

- Funcionalidades:

Autenticação: Login via e-mail/senha ou através de redes sociais (Twitter, Facebook)​(index).

Cadastro de Usuários: Criação de conta para novos usuários, com validações de campos obrigatórios​(cadastro).

Recuperação de Senha: Envio de link de recuperação de senha para o e-mail fornecido​(recuperacao_senha).

Feed de Notícias: Pesquisa e visualização de notícias relacionadas a temas ambientais​(feed).

Alertas de Desinformação: Sistema de alertas que notifica os usuários sobre desinformações ambientais circulando​(alert).

Notícias Salvas: Os usuários podem salvar e revisar notícias em uma página dedicada​(pagina_salvos).

Configurações de Conta: Personalização de idioma, notificações, e tema do aplicativo​(config).

- Como Executar o Projeto:

1) Clone ou faça o download dos arquivos HTML do projeto.
2) Abra o arquivo index.html em um navegador da web para iniciar o aplicativo.
3) Navegue pelas páginas através dos links disponíveis na interface do usuário.

- Dependências:

Tailwind CSS: O projeto utiliza o framework Tailwind CSS para estilização rápida e responsiva das páginas.
Font Awesome: Utilizado para ícones em diversas páginas.
