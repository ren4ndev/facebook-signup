# Projeto Facebook Signup Page

## Sobre o que é esse repositório?

Esse repositório é uma reprodução de um icônico layout que a maioria de vocês já devem ter visto! Estamos falando da tela de cadastro do Facebook.
O Facebook é a rede social mais acessada do mundo, com uma audiência de mais de 2.3 bilhões de usuários por mês. Espantoso, não? Para recriar a página inicial do Facebook, serão usadas muitas das skills de HTML, CSS e JavaScript aprendidas.

## Qual é o objetivo desse projeto?

Um dia você possivelmente estarei em uma situação em que terei que criar uma tela de cadastro de uma grande empresa, como o Facebook. Por que não?
Quando esse dia chegar (e se chegar), gostaria de ter os conhecimentos necessários, não é mesmo? Para isso, é fundamental saber colocar em prática a implementação de um formulário em HTML, utilizando também bibliotecas que deixem seu trabalho mais rápido, fácil e bonito. Além disso, será possível muito, muito, muito sobre CSS Flexbox, que é uma maneira fácil e limpa de organizar os elementos da sua tela. Adeus às tabelas IHA!

## Requisitos Obrigatórios:

### 1 - Crie uma barra azul na parte superior da página com a classe top-bar :heavy_check_mark:

  Pontos importantes:
  * Esta barra deve possuir a classe top-bar
  * A classe top-bar deve determinar que o elemento é um flex container
  * A classe top-bar deve possuir a propriedade `background-color: rgb(66, 103, 178)`


### 2 - A barra superior deve conter o logotipo do Facebook no canto esquerdo com a classe facebook-logo :heavy_check_mark:

  Pontos importantes:
  * O logotipo deve estar alinhado a esquerda dentro da barra azul
  * Deve existir um elemento img com a classe facebook-logo
  * O atributo src do logotipo deve apontar para imgs/facebook-logo.png


### 3 - A barra superior deve conter um formulário de autenticação no canto direito :heavy_check_mark:

  Pontos importantes:
  * O formulário deve estar alinhado a direita dentro da barra azul
  * Existe formulário possui uma classe chamada facebook-login
  * O formulário deve ser um flex container


### 4 - Crie uma classe no CSS chamada form-group :heavy_check_mark:

  Pontos importantes:
  * Essa classe deve possuir a propriedade `diplay: flex`
  * Alinhe o eixo principal dessa classe para ser o eixo vertical


### 5 - Adicione o primeiro subcontainer com a classe form-group para agrupar o rótulo e campo "E-mail ou telefone" dentro do formulário criado na etapa 3 :heavy_check_mark:

  Pontos importantes:
  * Deve haver um container utilizando a classe `form-group` criada no passo anterior
  * Dentro do container `form-group` criado, deve haver um rótulo com o id user-email-phone-label e o texto "Email ou telefone"
  * Dentro do container `form-group` criado, abaixo do rótulo deve haver campo de entrada de texto para receber o email ou o telefone do usuário com o id user-email-phone'

### 6 - Adicione o segundo subcontainer com a classe form-group para agrupar o rótulo e campo "Senha" dentro do formulário criado na etapa 3 :heavy_check_mark:

  Pontos importantes:
  * Deve haver um novo container utilizando a classe `form-group` criada no passo 4
  * Dentro do novo container `form-group` criado, deve haver um rótulo com o id user-password-label e o texto "Senha"
  * Dentro do novo container `form-group` criado, abaixo do rótulo deve haver campo de entrada para senha com o id user-password

### 7 - Adicione o terceiro subcontainer com a classe form-control com o botão "Entrar" dentro do formulário criado na etapa 3 :heavy_check_mark:

  Pontos importantes:
  * Deve haver um novo container utilizando a classe `form-control` criada no passo anterior
  * Crie uma classe no CSS form-control com a propriedade `align-self: flex-end`
  * Dentro do novo container `form-control` criado, deve haver um botão com o id "button-login" e o texto "Entrar"
  * O botão deve estar alinhado a direita do campo de entrada para senha
  * Ao clicar no botão com o id #button-login deve exibir um alert com o valor do campo "Email ou telefone"

### 8 - Crie um container com a classe main-content abaixo da barra azul para agrupar o conteúdo principal da página :heavy_check_mark:

  Pontos importantes:
  * Crie um elemento com a classe main-content
  * O elemento deve ser um flex container no eixo horizontal
  * O elemento deve posicionado abaixo da barra azul


### 9 - Crie um subcontainer com a classe left-content para colocar o conteúdo do lado esquerdo dentro do container com a classe main-content :heavy_check_mark:

  Pontos importantes:
  * O subcontainer deve ter a classe left-content
  * A classe left-content deve ter uma largura de 800px
  * Dentro do container com a classe left-content deve existir um parágrafo com id facebook-slogan e o texto "O Facebook ajuda você a se conectar e compartilhar com as pessoas que fazem parte da sua vida."
  * Dentro do container com a classe left-content deve existir abaixo do parágrafo com id facebook-slogan uma imagem com id facebook-networking e o src com o endereço `imgs/networking.png`.


### 10 - Crie um subcontainer com a classe right-content para colocar o conteúdo do lado direito dentro do container com a classe main-content :heavy_check_mark:

  Pontos importantes:
  * O novo subcontainer deve ter a classe right-content
  * A classe right-content deve ter uma largura de 300px
  * Utilize na classe main-content a propriedade justify-content com o valor mais apropriado para alinhar os conteúdos
  * Dentro do subcontainer com a classe right-content deve existir um elemento h1 com o texto "Abra uma conta"
  * Dentro do subcontainer com a classe right-content deve existir um elemento com a classe quick-easy com o texto "É rápido e fácil." posicionado abaixo do texto "Abra uma conta"
  * Dentro do subcontainer com a classe right-content deve existir um elemento form abaixo do texto "É rápido e fácil."
  * O elemento com a classe right-content deve estar a direita do elemento com a classe left-content


### 11 - Crie um campo de entrada de texto para o nome do usuário dentro do formulário criado no requisito 10 :heavy_check_mark:

  Pontos importantes:
  * O campo deve ter o atributo name com o valor "firstname"
  * O campo deve ter um placeholder com o valor "Nome"


### 12 - Crie um campo de entrada de texto para o sobrenome do usuário dentro do formulário criado no requisito 10 :heavy_check_mark:
  Pontos importantes:
  * O campo deve ter o atributo name com o valor "lastname"
  * O campo deve ter um placeholder com o valor "Sobrenome"
  * Esse campo deve estar alinhado a direita do campo de Nome


### 13 - Crie um campo de entrada de texto para o celular ou email do usuário dentro do formulário criado no requisito 10 :heavy_check_mark:

  Pontos importantes:
  * O campo deve ter o atributo name com o valor "phone_email"
  * O campo deve ter um placeholder com o valor "Celular ou email"
  * Posicione esse campo abaixo do campo do nome do usuário


### 14 - Crie um campo de entrada para senha do usuário dentro do formulário criado no requisito 10 :heavy_check_mark:

  Pontos importantes:
  * O campo deve ter o atributo name com o valor "password"
  * O campo deve ser do tipo "password"
  * O campo deve ter um placeholder com o valor "Nova senha"
  * Posicione esse campo abaixo do celular/email


### 15 - Crie um campo de entrada para data de nascimento do usuário dentro do formulário criado no requisito 10 :heavy_check_mark:

  Pontos importantes:
  * Um rótulo abaixo do campo nova senha com o id label-birthdate e o texto "Data de nascimento"
  * O campo deve ter o atributo name com o valor "birthdate"
  * O campo deve ter um placeholder com o valor "dd/mm/aaaa"
  * Posicione esse campo abaixo do rótulo


### 16 - Crie um campo de entrada para gênero do usuário dentro do formulário criado no requisito 10 :heavy_check_mark:

  Pontos importantes:
  * Um rótulo abaixo do campo nova senha com o id label-gender e o texto "Gênero"
  * O campo deve ser formado por três `radio buttons` com as opções "Feminino", "Masculino" e "Personalizado"
  * Posicione os radio buttons para ficar na mesma linha
  * Posicione os radio buttons para ficar abaixo do label

### 17 - Crie um botão para finalizar o cadastro dentro do formulário criado no requisito 10 :heavy_check_mark:

  Pontos importantes:
  * Um botão com o texto "Cadastre-se" e id "facebook-register"
  * Deve ter a propriedade type igual a submit


### 18 - Validar se todos os campos foram preenchidos ao clicar no botão "Cadastre-se" :heavy_check_mark:
 
  Pontos importantes:
  * Exibir uma mensagem "Campos inválidos" dentro do formulário caso pelo menos um campo não esteja preenchido

### 19 - Adicione um novo campo de texto no formulário se a pessoa usuária selecionar a opção "Personalizado" no campo Gênero :heavy_check_mark:

  Pontos importantes:
  * O novo campo dever ser uma campo de texto com o atributo name "gender-custom" e um placeholder "Gênero (opcional)"
  * O novo campo deve estar posicionado entre as opções de gênero e o botão "Cadastrar-se"

### 20 - Substituir o conteúdo do container com a classe right-content se o formulário estiver completamente preenchido e validado :heavy_check_mark:

  Pontos importantes:
  * Deve haver um texto no modelo "Olá, Jonh Doe" (substitua John Doe pelo nome e sobrenome preenchido no formulário)
  * Exibir o e-mail ou telefone
  * Não exibir a senha
  * Exibir a data de nascimento
  * Caso a opção selecionada no campo Gênero seja Feminino exibir "Feminino"
  * Caso a opção selecionada no campo Gênero seja Masculino exibir "Masculino"
  * Caso a opção selecionada no campo Gênero seja Personalizado exibir "Personalizado":

## Requisito Bônus

**Esse requisito não é verificável pelo avaliador automático. Sua apresentação (opcional) será realizada durante o fechamento do dia seguinte ao final do projeto**

### Realize o desenvolvimento da versão mobile do Facebook.

![Página Facebook](./facebook-mobile.png)

---
