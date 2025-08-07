# Desafio Kobe Apps - Aplicativo Rick and Morty API

![Capa do Projeto](https://i.imgur.com/K75g1iO.png) 

Este repositório contém a solução desenvolvida para o desafio de construir um aplicativo em Flutter para listar e exibir detalhes de personagens da API de Rick and Morty.

---

## 🚀 Funcionalidades

As funcionalidades obrigatórias do desafio foram implementadas, incluindo:

* **Listagem de Personagens**: Uma lista rolante com cards exibindo a imagem e o nome de cada personagem.
* **Rolagem Infinita**: A lista carrega mais personagens automaticamente conforme o usuário rola a página para baixo.
* **Tela de Detalhes**: Ao clicar em um card, o usuário é redirecionado para uma tela que mostra informações detalhadas do personagem.
* **Navegação**: A navegação entre a tela de listagem e a de detalhes funciona corretamente.

---

## 🛠️ Arquitetura e Tecnologias

A solução foi desenvolvida utilizando a linguagem Dart e o framework Flutter. A arquitetura e as bibliotecas escolhidas para a construção do aplicativo são:

* **Arquitetura**: Utilizei o padrão **MVVM (Model-View-ViewModel)**. Essa abordagem me permitiu separar claramente a lógica de negócio (ViewModel) da interface de usuário (View), facilitando a manutenção e a escalabilidade do código.
* **Gerenciamento de Estado**: Para gerenciar o estado das telas, optei por uma abordagem simples e robusta, utilizando o `StatefulWidget` com um `FutureBuilder` para carregar dados assincronamente e um `ScrollController` para o carregamento infinito.
* **Comunicação com a API**: A comunicação com a API REST de Rick and Morty (`https://rickandmortyapi.com/`) foi realizada usando a biblioteca **`Dio`**. O `Dio` facilitou a configuração e o tratamento das requisições HTTP de forma eficiente.
* **Estilização**: Para a tipografia, utilizei a biblioteca **`Google Fonts`** para importar a fonte Lato, mantendo a consistência visual do projeto.

---

## ⚙️ Como Executar

Para rodar este projeto em sua máquina local, siga os passos abaixo:

1.  Clone este repositório:
    ```sh
    git clone [https://github.com/(seu-usuario)/kode_start_tmdb.git](https://github.com/(seu-usuario)/kode_start_tmdb.git)
    ```
2.  Navegue até a pasta do projeto:
    ```sh
    cd kode_start_tmdb
    ```
3.  Instale as dependências:
    ```sh
    flutter pub get
    ```
4.  Execute o aplicativo em um emulador, dispositivo físico ou navegador:
    ```sh
    flutter run
    ```

---

## 🎥 Demonstração

**(Aqui você pode inserir os GIFs ou vídeos do seu projeto, demonstrando as funcionalidades.)**

* **Listagem de Personagens e Rolagem Infinita**

    ![Rolagem Infinita](https://github.com/user-attachments/assets/6e44268e-cf03-40b8-ad37-b17c0acedd8e)


* **Detalhes do Personagem**

    <img width="351" height="765" alt="image" src="https://github.com/user-attachments/assets/efeb886f-93bb-43b0-b5b6-91f679fceebc" />
