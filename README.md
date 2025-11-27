# ia-fooocus
📘 Guia para Utilizar o Fooocus no Google Colab

Este repositório explica, de forma simples e objetiva, como os alunos podem usar o Fooocus, uma ferramenta de geração de imagens baseada em IA, diretamente no Google Colab, sem precisar instalar nada no computador.

✅ O que é o Fooocus?

O Fooocus é um gerador de imagens baseado em modelos de IA (como Stable Diffusion) que permite criar artes, personagens, objetos, cenários e muito mais a partir de descrições de texto.

Ele é ideal para aprender:

IA generativa

Prompting


▶️ Como executar o Fooocus no Google Colab
Acesse o Google Colab:
👉 https://colab.research.google.com

Crie um novo notebook.

Cole o seguinte código na primeira célula:

!pip install pygit2==1.15.1
%cd /content
!git clone https://github.com/lllyasviel/Fooocus.git
%cd /content/Fooocus
!python entry_with_update.py --share --always-high-vram


Clique no botão ▶️ Executar (ou use Shift + Enter).

Aguarde a instalação (leva alguns minutos).

Após finalizar, o Colab mostrará um link público (Share link) para acessar a interface do Fooocus.

Abra o link e comece a gerar imagens utilizando prompts!
