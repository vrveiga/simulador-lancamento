# Orb
## Simulador de lançamento com força gravitacional

### Descrição básica do projeto
Orb é o simulador físico que usa força gravitacional para calcular a trajetória de um planeta ao redor de uma estrela e a energia envolvida no sistema. A ideia foi conseguir visualizar como diferentes condições iniciais mudam a trajetória e velocidade e a troca de energia potencial e cinética ao longo do tempo.
Para isso, criamos um programa em python que simula a gravitação newtoniana, com uma interface gráfica que permite ao usuário definir os parâmetros iniciais, visualizar o movimento planetário e recomeçar várias vezes.

### Implementação

- Linguagens e pacotes:
Este projeto utiliza apenas a linguagem Python (o código é compatível com as versões 3.10 e adiante) e as bibliotecas Numpy e Pygame. O Numpy nos permite rapidamente realizar os cálculos com vetores usados na simulação, enquanto o Pygame nos permite facilmente implementar a parte gráfica e interativa.

### Como usar

- Instalação
  Antes de tudo, certifique-se de ter instalado em seu computador o interpretador de Python configurado para as versões 3.10 e mais recentes. No Windows, isso pode ser feito na Microsoft Store, pesquisando "Python" e instalando a versão mais recente, ou ainda usando o Visual Studio Code, com um pacote da linguagem. No Linux, instale o pacote da linguagem que sua distribuição oferece: [Debian/Ubuntu e Fedora](https://python.org.br/instalacao-linux/) ou [Arch](https://wiki.archlinux.org/title/Python_(Portugu%C3%AAs))
- Dependências
  Como dito, o programa usa Pygame e Numpy, bibliotecas do Python que podem ser mais facilmente baixadas usando o instalador oficial de pacotes do Python, o pip:

  ```sh
  pip install numpy
  pip install pygame
  ```
- Execução
  Tudo instalado, apenas execute a main:

  ```sh
  python main.py
  ```
  
  Uma tela irá aparecer. Nela, você poderá ajustar os parametrôs iniciais clicando nos números e digitando-os. Pode-se ajustar:
  
   - massa da estrela em 1e16 kg
   - massa do planeta em kg
   - posição inicial do planeta em metros
   - velocidade inicial do planeta em m/s

  Após inserir os valores desejados, clique em "Começar" e a simulação será apresentada.
  
### Informações sobre o projeto
Este projeto foi desenvolvido por:

```
Felipe Cerri: 
João Gabriel Araújo de Bastos: joaog.bastos@usp.br
João Pedro Monteiro Machado Junqueira Castelli: jotapcastelli@usp.br
Matheus Muzza Pires Ferreira: matheusmpf@usp.br
Marcelo Martins Conti: marcelo.mmartins@usp.br
Vitor Rocha Veiga: vitorveiga@usp.br
```

## Referências:
(1) Bernardes, E. de S. (2024). Gravitação (Notas de aula). 7600105 - Física Básica I. Universidade de São Paulo, São Carlos.
