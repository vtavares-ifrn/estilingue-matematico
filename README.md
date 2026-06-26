# 🎯 Estilingue Matemático

Um jogo educativo e interativo desenvolvido em HTML, CSS e JavaScript Vanilla (Canvas API) com o objetivo de transformar o aprendizado de funções de segundo grau em um desafio visual e divertido. 

Em vez de decorar fórmulas no quadro, o jogador precisa aplicar a matemática na prática: manipulando os coeficientes da equação da parábola ($y = ax^2 + bx + c$) para calcular a trajetória de um projétil e destruir os alvos espalhados pelo cenário.

## 🚀 Funcionalidades

* **Sistema de Fases Infinito:** Geração procedural de alvos e cenários (alternando entre gravidade normal e invertida).
* **Escala Matemática Didática:** O plano cartesiano foi otimizado para trabalhar com dezenas, evitando contas com números exatos na casa dos milhares e focando a atenção no cálculo da parábola.
* **Modo Difícil (Hard Mode):** Adiciona muros gerados dinamicamente no caminho, forçando o jogador a calcular o vértice da parábola para que o tiro passe por cima (ou por baixo) do obstáculo.
* **Calculadora Embutida:** Um painel lateral de ferramentas para auxiliar nas contas rápidas sem precisar sair da tela do jogo.
* **Sistema de Combos:** Mecânica de tiro "perfurante" (piercing). Se a parábola for perfeitamente calculada para atravessar múltiplos alvos no mesmo lançamento, os pontos são multiplicados.
* **Feedback Visual:** Efeitos dinâmicos de rastro de cometa e partículas de desintegração nos alvos (Caixotes, Cofrinhos e Cofres Fortes).

## 🎮 Como Jogar

1. Analise o cenário e passe o mouse sobre os alvos ou obstáculos para descobrir suas coordenadas `X` e `Y`.
2. Use seus conhecimentos matemáticos para encontrar as raízes ou o vértice ideal.
3. Preencha os valores de `A` e `B` na equação $y = ax^2 + bx + c$ na parte inferior da tela (O valor de `C` é definido pela altura inicial fixa da fase).
4. Clique em **LANÇAR!** e assista a física agir.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação do layout e controles numéricos.
* **CSS3:** Estilização responsiva, Dark Mode atrelado à dificuldade e interface baseada em Flexbox/Grid.
* **JavaScript Vanilla:** Lógica do jogo, sistema de colisão (Bounding Box), loop de renderização a 60fps (Game Engine própria) e manipulação do HTML Canvas para os desenhos vetoriais e animações.

## 💡 Objetivo Didático

Este projeto foi criado com o propósito de facilitar o ensino de matemática básica e introdução ao pensamento computacional. É uma ferramenta excelente para testar a compreensão lógica do comportamento das curvas gráficas antes de avançar para conceitos mais complexos.
