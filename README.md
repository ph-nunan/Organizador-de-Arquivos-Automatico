# ORGANIZADOR DE ARQUIVOS - DESKTOP - AUTOMAÇÃO

Este é um script Python que visa automatizar a organização de arquivos em um diretório selecionado pelo usuário. Ele utiliza a biblioteca tkinter para criar uma caixa de diálogo que permite ao usuário escolher uma pasta a ser organizada.





## VISÃO GERAL

 O Organizador de Arquivos é uma ferramenta desenvolvida em Python para simplificar a tarefa de organizar e categorizar arquivos em uma pasta selecionada pelo usuário. O projeto visa resolver o desafio comum de lidar com uma grande quantidade de arquivos desorganizados, facilitando a classificação e o acesso posterior.

### Propósito

O propósito principal do projeto é simplificar a organização de arquivos, economizando tempo e esforço para os usuários que frequentemente se encontram lidando com uma variedade de tipos de arquivos em um único diretório. Em vez de realizar manualmente a tediosa tarefa de criar pastas separadas para diferentes tipos de arquivos e movê-los manualmente, o Organizador de Arquivos automatiza esse processo, aumentando a eficiência e melhorando a organização do sistema de arquivos.

### Problema Resolvido

Muitas vezes, os usuários enfrentam a desorganização em seus sistemas de arquivos, resultante da mistura de vários tipos de arquivos em um mesmo local. Isso não apenas dificulta a localização rápida de arquivos específicos, mas também pode levar à perda de tempo ao procurar itens importantes. O Organizador de Arquivos resolve esse problema, categorizando automaticamente os arquivos em subpastas de acordo com suas extensões, tornando a organização do sistema de arquivos mais estruturada e acessível.

### Público-Alvo

O projeto destina-se a uma ampla gama de usuários que lidam com arquivos em seus computadores regularmente. Isso inclui estudantes que precisam gerenciar arquivos de diferentes disciplinas, profissionais que trabalham com diversos tipos de documentos e mídia, bem como qualquer pessoa que deseje manter seu sistema de arquivos mais organizado. O Organizador de Arquivos é particularmente útil para aqueles que desejam otimizar sua produtividade, reduzindo a desordem em seus diretórios de arquivos.

## CAPTURAS DE TELA

![organizador de arquivos](https://github.com/ph-nunan/Organizador-de-Arquivos-Automatico/assets/117214802/e5751011-26e8-4ac7-bb28-533607ce9871)



## FUNCIONALIDADES PRINCIPAIS

### Seleção de Pasta: 

O Organizador de Arquivos permite aos usuários selecionar facilmente a pasta que desejam organizar por meio de uma interface amigável.

### Categorização Automática:

O projeto automaticamente identifica a extensão de cada arquivo na pasta selecionada e o associa a uma categoria predefinida, como "imagens", "planilhas", "aplicativos", etc.

### Criação de Subpastas: 

Caso a categoria correspondente ainda não exista na pasta selecionada, o script cria automaticamente a subpasta correspondente para armazenar os arquivos daquela categoria.

### Movimentação de Arquivos: 

Os arquivos são movidos automaticamente para suas respectivas subpastas, tornando o processo de organização uma tarefa sem esforço.

### Flexibilidade: 

O usuário tem a capacidade de adicionar, remover ou modificar as extensões e categorias no dicionário "locais", personalizando assim o processo de organização de acordo com suas necessidades.

### Otimização de Tempo:

Ao automatizar o processo de organização, o projeto economiza tempo precioso, substituindo o trabalho manual demorado pela organização rápida e precisa.

### Melhoria da Produtividade:

Com um sistema de arquivos mais organizado, os usuários podem localizar e acessar seus arquivos com mais rapidez, aumentando a eficiência em suas tarefas diárias.

### Redução de Desordem: 

A funcionalidade de categorização automática ajuda a evitar a desordem e a confusão causadas por uma grande variedade de arquivos desorganizados.

### Acessibilidade: 

Projetado para atender a uma ampla gama de usuários, desde estudantes até profissionais, o projeto oferece uma solução acessível para a organização de arquivos.

### Personalização: 

Os usuários têm a liberdade de adaptar as categorias e extensões às suas preferências, permitindo uma experiência de organização altamente personalizada.










## TECNOLOGIAS UTILIZADAS

### Python:

 A linguagem de programação principal utilizada no projeto.
### os:

Biblioteca padrão do Python usada para interagir com o sistema operacional, manipular caminhos de arquivos, criar diretórios, renomear arquivos, etc.
### tkinter:
  
Uma biblioteca gráfica do Python para criar interfaces gráficas de usuário (GUI). No código, é usada para criar uma caixa de diálogo para selecionar a pasta.
### askdirectory:

Função da biblioteca tkinter.filedialog usada para exibir uma caixa de diálogo para selecionar uma pasta.





## PRÉ-REQUISITOS

### Python: 

O projeto requer uma instalação funcional do Python. Certifique-se de ter o Python instalado em sua máquina. Você pode baixar o Python em python.org.

### Biblioteca tkinter: 

O projeto utiliza a biblioteca tkinter para a interface gráfica de usuário. Normalmente, essa biblioteca já está incluída na instalação padrão do Python. Certifique-se de que ela esteja disponível em sua instalação.




## OBSERVAÇÕES

- Instale o Python: Se você ainda não tiver o Python instalado, baixe e instale a versão mais recente do Python em python.org.

- Se atente aos imports:

```bash
import os
from tkinter.filedialog import askdirectory
```



## AUTOR

Paulo Nunan



## LICENÇA

MIT




## AGRADECIMENTOS

Conhecimento adquirido através dos cursos: Alura, CodeAcademy,youtube + faculdade de Eng. de Software.
