<h1><br>
<p align=`center`>
Configuração Eslint para projetos typescript NextJs | ReactJs
</p>
</h1>

## Instalação

basta instalar através do npm (ou gerenciador favorito):

```shell
npm i eslint-typescript-saturnino

yarn add eslint-typescript-saturnino
```

## Uso

Basta adicionar no seu `.eslintrc.json`:

```javascript
{
  // ...
  `extends`: `eslint-typescript-saturnino`
  // ...
}
```

<h1><br>
<p align=`center`>
Pacotes incluídos na instalação.
</p>
</h1>

`eslint:` Essa é a própria lib do ESLint, que é uma ferramenta de análise de código estática para JavaScript. É necessário instalá-la para utilizar o ESLint em um projeto.

`eslint-config-prettier:` Essa lib desativa todas as regras do ESLint que possam entrar em conflito com as configurações do Prettier, que é uma ferramenta de formatação de código. Isso evita erros de formatação e torna a integração entre as duas ferramentas mais fácil.

`eslint-config-standard-with-typescript:` Essa é uma configuração padrão do ESLint com suporte a TypeScript. Ela define as regras que serão usadas para analisar o código e garantir a qualidade e consistência.

`eslint-plugin-import:` Esse plugin adiciona regras para a importação de módulos em um projeto. Ele ajuda a manter a consistência na importação e a evitar erros comuns, como importações duplicadas ou não utilizadas.

`eslint-plugin-import-helpers:` Esse plugin permite definir regras personalizadas para a ordem de importação e agrupamento de módulos em um arquivo. Ele ajuda a manter a organização do código e a evitar erros comuns na importação.

`eslint-plugin-n:` Esse plugin adiciona regras para o uso de números em um projeto. Ele ajuda a evitar erros comuns, como o uso de números mágicos ou valores numéricos sem unidade de medida.

`eslint-plugin-next:` Esse plugin adiciona regras específicas para projetos usando o framework Next.js. Ele ajuda a garantir a qualidade do código e evitar erros comuns na estrutura do projeto.

`eslint-plugin-prettier:` Esse plugin adiciona a opção de usar o Prettier como um formatador de código dentro do ESLint. Ele ajuda a garantir a formatação consistente do código e evitar erros de formatação.

`eslint-plugin-promise:` Esse plugin adiciona regras para o uso de promessas em um projeto. Ele ajuda a evitar erros comuns, como o uso incorreto de promessas ou a falta de tratamento de erros.

`eslint-plugin-react:` Esse plugin adiciona regras para o uso do React em um projeto. Ele ajuda a garantir a qualidade do código e evitar erros comuns na estrutura do projeto.

`eslint-plugin-unused-imports:` Esse plugin adiciona regras para identificar importações de módulos que não estão sendo utilizadas em um projeto. Ele ajuda a garantir a eficiência do código e evitar erros de importação desnecessários.

<h1><br>
<p align=`center`>
Regras configuradas.
</p>
</h1>

`@typescript-eslint/no-misused-promises: 0` - Desativa a regra que proíbe o uso indevido de promessas.

`@typescript-eslint/no-floating-promises: 0` - Desativa a regra que proíbe a criação de promessas que não são tratadas ou rejeitadas.

`@typescript-eslint/consistent-type-assertions: 0` - Desativa a regra que exige coerência na sintaxe de assertions de tipos.

`@typescript-eslint/strict-boolean-expressions: 0` - Desativa a regra que exige a verificação explícita de valores booleanos em determinadas expressões.

`@typescript-eslint/no-unused-vars: [error, {argsIgnorePattern: ^_}]` - Define a regra que reporta variáveis não utilizadas, mas ignora variáveis que começam com um sublinhado.

`react/prop-types: 0` - Desativa a regra que exige declaração de propTypes para componentes React.

`no-console: 0` - Desativa a regra que proíbe o uso de console.log e outros métodos da API de console.

`semi: [warn, never]` - Define que o ponto-e-vírgula no final de uma instrução deve ser omitido, gerando um aviso caso seja adicionado.

`quotes: [error, single]` - Define que as aspas simples devem ser usadas para delimitar strings.

`react/jsx-one-expression-per-line: [error, {allow: single-child}]` - Define que cada expressão dentro de um componente JSX deve estar em uma linha separada, exceto quando a expressão é única.

`max-len: [error, {code: 120, ignoreComments: true, ignoreUrls: true}]` - Define que uma linha de código não deve ter mais de 120 caracteres, ignorando comentários e URLs.

`linebreak-style: [error, unix]` - Define que o formato das quebras de linha deve ser do tipo Unix.

`react/jsx-indent: [error, 2]` - Define que as expressões JSX devem ser indentadas com 2 espaços.

`no-else-return: [error]` - Define que a cláusula `else` deve ser evitada quando possível.

`object-curly-spacing: [error, always]` - Define que as chaves que delimitam objetos devem ter espaços em branco antes e depois.

`no-multiple-empty-lines: [error, {max: 1}]` - Define que no máximo uma linha em branco consecutiva é permitida.

`react/react-in-jsx-scope: off ` - Desativa a regra que exige a importação do React em todos os arquivos que contêm código JSX.

`unused-imports/no-unused-imports: 2` - Define que uma importação não utilizada deve ser reportada como erro.

`@typescript-eslint/explicit-function-return-type: 0` - Desativa a regra que exige que as funções tenham um tipo de retorno explícito.

`import-helpers/order-imports:` - Define a ordem de importação dos módulos e pacotes, agrupando-os por categorias e especificando a ordem alfabética dentro de cada categoria.
