INSPIRE O REINO

Visão Geral

O projeto "Inspire o Reino" consiste em uma aplicação web e um aplicativo móvel que permitem aos usuários lerem e explorarem a Bíblia Sagrada de forma interativa. O projeto é dividido em duas partes principais:

Website "Inspire o Reino": Um site web responsivo onde os usuários podem selecionar livros, capítulos e versículos da Bíblia para leitura. O site oferece uma experiência de usuário simples e intuitiva, permitindo aos usuários acessarem facilmente os textos bíblicos desejados.

Aplicativo "Inspire o Reino" para Dispositivos Móveis: Um aplicativo móvel desenvolvido com o framework Kivy, disponível para dispositivos Android, que permite aos usuários lerem os textos bíblicos em seus smartphones ou tablets. O aplicativo oferece uma interface fácil de usar e recursos básicos para navegar pelos livros, capítulos e versículos da Bíblia.

Funcionalidades
Website "Inspire o Reino"
Seleção de Livros: Os usuários podem escolher entre os diferentes livros da Bíblia disponíveis.
Seleção de Capítulos e Versículos: Após selecionar um livro, os usuários podem escolher o capítulo e o versículo desejados.
Exibição de Versículos: O site exibe o texto do versículo selecionado para leitura.
Navegação entre Versículos: Os usuários podem navegar entre os versículos de um capítulo usando botões específicos.
Recurso de Ouvir: Os usuários podem ouvir a leitura do versículo selecionado por meio do recurso de sintetização de voz do navegador.
Aplicativo "Inspire o Reino" para Dispositivos Móveis
Seleção de Livros: Os usuários podem escolher entre os diferentes livros da Bíblia disponíveis usando um menu suspenso.
Seleção de Capítulos: Após selecionar um livro, os usuários podem escolher o capítulo desejado.
Exibição de Capítulo: O aplicativo exibe o texto completo do capítulo selecionado para leitura.
Navegação entre Capítulos: Os usuários podem navegar entre os capítulos do livro selecionado.
Interface Responsiva: O aplicativo é desenvolvido usando o framework Kivy, que oferece suporte a layouts responsivos para diferentes tamanhos de tela de dispositivos móveis.
Integração de Dados: O aplicativo carrega os dados da Bíblia a partir de um arquivo JSON local.
Tecnologias Utilizadas
Flask: Utilizado para criar o servidor web e fornecer os endpoints necessários para a comunicação com o frontend.
Kivy: Framework Python para o desenvolvimento de aplicativos multiplataforma, utilizado para criar o aplicativo móvel.
HTML/CSS: Utilizados para criar a interface do usuário do website.
JavaScript: Utilizado para manipulação de eventos e interações do usuário no frontend do website.
JSON: Utilizado para armazenar os dados da Bíblia, que são carregados tanto pelo site quanto pelo aplicativo móvel.
Estrutura do Projeto
O projeto está estruturado da seguinte forma:

bible.py: Script Python que implementa o servidor Flask para o website.
bibleandroid.py: Script Python que implementa o aplicativo móvel usando o framework Kivy.
acf.json: Arquivo JSON contendo os dados da Bíblia.
index.html: Arquivo HTML que define a estrutura e o layout da página inicial do website.
style.css: Arquivo CSS que define o estilo e a aparência do website.
README.md: Documentação do projeto que descreve suas funcionalidades, tecnologias utilizadas e estrutura do projeto.
Execução do Projeto
Para executar o projeto:

Clone o repositório do GitHub em seu ambiente de desenvolvimento.
Certifique-se de ter o Python e as dependências necessárias instaladas em seu sistema.
Execute o script bible.py para iniciar o servidor Flask do website.
Execute o script bibleandroid.py para iniciar o aplicativo móvel usando o Kivy framework.
Certifique-se de que o arquivo acf.json está presente no diretório do projeto para que os dados da Bíblia possam ser carregados corretamente.

Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema, ou deseja adicionar novos recursos, sinta-se à vontade para abrir uma issue ou enviar um pull request no repositório do GitHub.

Autor
Este projeto foi desenvolvido por Ronan Alles.
