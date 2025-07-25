# Comparação de Algoritmos de Substituição de Páginas: FIFO vs. Envelhecimento.

Este projeto implementa e compara dois algoritmos de substituição de páginas: FIFO (First-In, First-Out) e Aging.
O objetivo é analisar o desempenho de cada algoritmo em termos de faltas de página, variando a quantidade de molduras de páginas disponíveis.

## Equipe

- Alyne Matos
- Geovana Castro
- Larissa Vieira
- Victor França

## Descrição

O projeto simula o comportamento de processos acessando a memória, gerando sequências de referências de páginas, e calcula o número de faltas de página para os algoritmos FIFO e Aging.
Os resultados são apresentados para diferentes quantidades de molduras de páginas, permitindo uma comparação direta entre os dois algoritmos.


## Conclusões

Aumento das Molduras: à medida que o número de molduras aumenta, o número de faltas de página diminui para ambos os algoritmos.
Eficiência Relativa: o algoritmo Aging tende a ser mais eficiente que o FIFO em cenários com maior variação de acesso, pois leva em conta o histórico de uso das páginas.
