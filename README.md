# docker-mean-stack
Uma aventura pelo mundo do docker e como implementar essa ferramenta com a mean stack


## THE MEAN STACK
- MongoDB
- Node.js + Express.js
- Angular.js (v1.6.9)

(Nginx vai ser o responsável pelo Reverse Proxy e Web Server)

todas as requisições que precisam de uma conexão com o banco de dados, foi agrupado em URL's que começam com "/api/"

#### Benefícios de Microsserviços
1. Componentes são facilmente substítuiveis
2. Experiência do usuário melhorada devido a indepedência dos componentes entre si, logo, se o banco de dados parar, a interface do Angular não é afetada diretamente, e o usuário receberá uma mensagem de que o servidor está em manutenção, e não aparecerá simplesmente uma tela branca ou que a página não foi encontrada
3. Os desenvolvedores podem trabalhar autonomamente sem suas mudanças interferirem diretamente nos outros componentes
4. Aplicação facilmente escalável e implantável