<h1 style="text-align: center; margin-bottom: 0">
  <img src=".github/shift-icon.png" alt="Shift INC Logo"> Shift INC
</h1>
<h1 style="text-align: center">
  Frontend Developer Challenge
</h1>

## 🌆 Layout

Desktop           |           Mobile
:-------------------------:|:-------------------------:
![Desktop layout](/layout/desktop.jpg) | ![Mobile layout](/layout/mobile.jpg)

O layout está dentro da pasta `layout`, neste ponto avaliaremos como você seguirá o layout disposto em formato não aberto para entendermos como você lida com dificuldades que possam aparecer neste sentido, desde o espaçamento até as cores que são utilizadas no layout.

- Aqui avaliaremos especificamente para todos:
  1. Como o código foi criado e estruturado.
  2. Como foi feito semânticamente.

Dentro do layout temos 4 partes:

1. Header.

2. Menu.

3. Perfil.

4. Repositórios.
    - Aqui também avaliaremos:
      1. Pesquisa, ordenação e filtro.

**Dica/Importante**: Aqui avaliaremos cada parte de forma separada, por isto, sugerimos que seja criado 4 componentes, sendo eles: `header`, `menu`, `perfil` e `repositórios`, todos sendo importados e utilizados na mesma página.

## 🥇 Critérios técnicos que avaliaremos do projeto todo

- Usar algum framework frontend (Vue ou React).

- Usar Typescript.

- Usar a API do GitHub.

- Seguir o layout proposto (desk e mobile).

- Uso do git e padronização dos commits.

  - Sugerimos a utilização de micro commits conforme for avançando no projeto e **[mensagens semânticas de commit](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)**.

- Organização dos arquivos do projeto.

- Construção de **HTML** e **SCSS** estruturado, organizado e semântico.

- Boas práticas na utilizaçao de **JavaScript** e **TypeScript**.

- Responsividade (mobile, tablet e desktop).

## 🔄 API GitHub

Link para a API do GitHub [aqui](https://docs.github.com/pt/rest/guides/getting-started-with-the-rest-api).

## 🖌 Cores

`header -> #161b22`
`background -> #0d1117`
`border -> #21262d`
`white -> #c9d1d9`
`text-muted -> #8b949e`
`link -> #58a6ff`
`border-active -> #F78166`

## 📋 Instruções

- Após o término do desafio, subir em um repositório do GitHub e liberar o acesso para o e-mail: gabriel.haddad@shiftinc.com.br.

## 🍀 Nossas dicas para o desenvolvimento do projeto

1. Antes de iniciar o desenvolvimento, avalie o layout e tente mapear e entender o que o layout precisa em relação a eventos (hover, condicional para exibição de dados) e quais componentes você precisará criar (nós recomendamos que cada repositório seja um componente proprio por exemplo).

2. **Não** utilize nenhum **framework de estilização** (exemplo: boostrap, materialize...), vamos avaliar o seu nível de conhecimento em css/scss.

3. Tente seguir boas práticas de código, avaliaremos a hierarquia utilizada tanto no HTML quanto no SCSS. Em Javascript, avaliaremos como foi feito a criação e utilização de variaveis e código.

4. Recomendamos que haja separação de responsabilidade dentro dos componentes, tanto de estilização quanto de customização de código javascript que seja criado para fazer uso de condicionais por exemplo.

5. A utilização de tipagens via typescript é importante e será avaliada.

6. Para a parte de formulário avaliaremos a utilização de tags nativas do HTML, tanto para validação quanto para o envio do formulário.

7. Preencha o arquivo de [Feeback do projeto](FEEDBACK_PROJETO.md) contando para nós o que fez, o que não fez e a sua avaliação sobre o teste.

## 😉 Não conseguiu finalizar o teste?

Não tem problemas, envie mesmo assim, nós vamos avaliar o teste mesmo que não esteja finalizado dando prioridade aos seguintes pontos:

- Como o projeto ficou estruturalmente e se foi utilizado boas práticas.

- Qual lógica você seguiu no código para resolver, contornar os problemas ou implementações que precisou fazer.

- Qual prioridade você deu no desenvolvimento do layout.

- Quais detalhes você implementou (exemplo: hover, eventos de validação...)

## 🤔 Dúvidas ?

Caso tenha alguma dúvida, envie um e-mail para **gabriel.haddad@shiftinc.com.br** com o titulo contendo o prefixo: `[Frontend Challenge]`

Exemplo: `[Frontend Challenge] posso utilizar vite ?`
