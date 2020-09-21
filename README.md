# DS Pesquisa
Aplicação com enquete / pesquisa de jogos favoritos. Pode ser utilizada e personalizada para qualquer tipo de pesquisa.

### Tecnologías
- ReactJS / React Native 
- Java / Spring Boot
- PostgreSQL

### Demonstração
- Front WEB: [Acessar](https://sds1-tyandrer.netlify.app/) "Hospedagem Free, pode demorar o carregamento" 
- Front Mobile:

![](https://i.imgur.com/epsafTI.png)

### Ferramentas utilizadas
- Spring Tools Suite Eclipse
- VScode
- Docker
- Node 
- Yarn
- Expo

### Instalação
Considerando o mesmo cenário de ferramentas
- Fazer download do repositório
- Carregar uma imagem PostgreSQL no Docker
#### Backend
- Abrir o projeto "/backend" no STS (Spring Tools Suite)
- Modificar as variações do "application.properties" com as suas credenciais
- Alterar o "application.properties" para modo "TEST"
- Iniciar a aplicação
#### Front - WEB
- Abrir o projeto "/front-web" no VScode
- Executar:
```sh 
yarn 
```
- Alterar o BASE_URL dos arquivos abaixo para o endereço do seu backend:
-- /src/pages/Charts/index.tsx
-- /src/pages/Records/index.tsx
- Executar:
```sh 
yarn start
```
#### Front - Mobile
- Abrir o projeto "/front-mobile" no VScode
- Executar:
```sh 
yarn 
```
- Alterar o BASE_URL dos arquivos abaixo para o endereço do seu backend:
-- /src/pages/CreateRecord/index.tsx
- Executar:
```sh 
yarn start
```
- Abrir o App do expo no celular e carregar o "QRcode"

Licença
----

MIT

**Free Software, ;) .**
