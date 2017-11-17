# Desafio de Frontend - Pet Nativa

**Proposta:**
Desenvolver uma aplicação *client-side* que, ao consultar a GitHub API, apresente os repositórios mais populares de um determinado usuário. A aplicação desenvolvida deve funcionar nos navegadores mais recentes do mercado, além de ser responsiva.

Este desafio irá testar suas capacidades com JavaScript, Vue/React (e Vuex/Redux), assim como suas habilidades para interagir eficientemente com APIs.

**API de apoio:** https://developer.github.com/v3/

## Requisitos
- Como um usuário (candidato), eu quero buscar por um usuário do GitHub, para que possa ver os repositórios mais populares desse usuário

- Como um usuário (candidato), eu quero ver os detalhes do usuário que busquei (nº de seguidores, nº de seguidos, avatar, e-mail e bio), para que possa saber mais sobre o usuário

- Como um usuário (candidato), eu quero ver a listagem dos repositórios do usuário que busquei, ordenados em ordem decrescente pelas estrelas (do repositório), para que possa ver quais são os repositórios favoritados do usuário

- Como um usuário (candidato), eu quero alterar a ordem da listagem de repositórios, para que possa analisá-la em ordem crescente (por exemplo)

- Como um usuário (candidato), eu quero ver uma página detalhada de cada repositório (nome, descrição, nº de estrelas, linguagem principal e *link* para o repositório) na listagem, para que eu possa entender o conteúdo de cada repositório e acessar os que me interessar

## Definition of Done
- **Ser responsivo!** Deve atender dispositivos com a resolução no mínimo de 320 x 480;
- Não é obrigatório o uso de um *framework*, mas **recomendamos Vue.js** ou React.js.
- **É obrigatório o uso de rotas.**

## Critérios de Avaliação
- *Organização:* o projeto está bem estruturado, documentado e faz uso de Git?
- *Tecnologia:* utiliza as tecnologias mais recentes (e estáveis) do mercado?
- *Coerência:* os requisitos foram atendidos?
- *Boas práticas:* o projeto segue boas práticas de desenvolvimento, incluindo segurança e otimização?
- *Qualidade:* possui testes automatizados e integração contínua?

#### Pontos Extras
- Uso de pré processador CSS (SASS, LESS ou Stylus)
- Uso de pós processador CSS (PostCSS)
- Gerenciador de Estados (Vuex ou Redux)
- Documentação
- Não usar jQuery e nem Bootstrap ;)
- Layout bonito
    - Tabelão com tudo faz voltar 5 casas

## Observação

A performance e a adequação dos recursos serão considerados durante o processo de avaliação. Alem disso, a avaliação ocorrerá em todos os componentes do projeto (JavaScript, HTML e CSS).

As APIs a serem consumidas são:

**1. Detalhes de um usuário -** https://api.github.com/users/{username}

**2. Repositórios de um usuário -** https://api.github.com/users/{username}/repos

**3. Detalhes de um repositório -** https://api.github.com/repos/{full_name}

## Processo de submissão

O desafio deve ser entregue pelo GitHub. A aplicação deve estar hospedada (Heroku, Firebase, etc). As URLs devem constar no README.

Qualquer dúvida em relação ao desafio, responderemos por e-mail.

Bom trabalho!
