# wordpress-moodle
Integração do Woordpress e Moodle.

#Instalação: 

* Baixe a biblioteca de senha: http://www.openwall.com/phpass/ 
* Cole biblioteca de senha na pasta "sua_instalacao_do_moodle/lib/" 
* Substitua os arquivos: auth.php e config.html ambos ficam no diretório: "sua_instalacao_do_moodle/auth/db/" 

#Configuração: 

* No menu: Plugins>Autenticação>Gerenciar autenticação 
* Habilite a opção "Use um banco de dados externo". 
* Clique em configurações. 
* Preencha os campos de host, Nome do BD, Usuário do BD e senha de acordo com sua instalação do Wordpress. 
* Informe a tabela de usuários do Wordpress: wp_users 
* Informe a coluna de usuário e senha dos usuários do Wordpress: user_login e user_pass 
* Em Formato da senha selecione wordpress (Adicionado no arquivo config.html) 
* No campo "Página de mudança de senha" coloque sua página do Wordpress responsável por isso.

Agora você pode criar uma nova conta no Wordpress e tentar fazer login no Moodle com as credenciais recém criadas, se tudo deu certo você será redirecionado para página de Perfil do Moodle e irá completar suas informações.



