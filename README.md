# Desafio - Criando um hook de carrinho de compras

### Sobre o desafio

O desafio consiste em criar uma aplicação para treinar o que foi abordado até agora (Capítulo 2) no ReactJS.
Essa será uma aplicação onde o principal objetivo é criar um hook de carrinho de compras. Composta de duas páginas, um componente e um hook para implementar as funcionalidades pedidas nesse desafio:

- Adicionar um novo produto ao carrinho;
- Remover um produto do carrinho;
- Alterar a quantidade de um produto no carrinho;
- Cálculo dos preços sub-total e total do carrinho;
- Validação de estoque;
- Exibição de mensagens de erro;
- Entre outros.

### Template da aplicação
https://github.com/rocketseat-education/ignite-template-reactjs-criando-um-hook-de-carrinho-de-compras

### Fake API com JSON Server
Foi utilizado o JSON Server para simular uma API que possui as informações das comidas. 
Navegue até a pasta criada, abra no Visual Studio Code e execute os seguintes comandos no terminal:

```bash
yarn
yarn server
```

 Será inicializado uma fake API com o recurso /foods em localhost na porta 3333 a partir das informações do arquivo server.json localizado na raiz do seu projeto.
 
 ### Para inicializar a aplicação
 
 ```bash
yarn start
```

### O que foi editado na aplicação?
- src/components/Header/index.tsx;
- src/pages/Home/index.tsx;
- src/pages/Cart/index.tsx;
- src/pages/Cart/index.tsx;


### Como a aplicação ficou no final

![rocketshoes](https://user-images.githubusercontent.com/26827923/133709744-db45db67-dfaf-4b47-87b8-80b15075e671.png)

![carrinho](https://user-images.githubusercontent.com/26827923/133709789-73cfe608-7452-4c26-a1b2-3256b5c92f3e.png)
