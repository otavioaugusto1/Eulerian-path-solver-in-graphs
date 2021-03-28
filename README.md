# Eulerian-path-solver-in-graphs
A Eulerian path solver in graphs using python, glucose-syrup and converttoCNF.

1º: ao descompactar o arquivo, entrar até a pasta "simp" dentro do glucose-syrup. (Considerar já possuir o g++, make, libz, glucose-syrup, python e o convertto instalados)
2º: após isso executar:    export PATH="$PATH:/home/otavio/glucose-syrup-4.1/simp/"
3º: sair da pasta "simp" e executar:  g++ -std=c++11 -o converttoCNF converttoCNF.cpp
4º: após executar o comando anterior, executar:   ./converttoCNF
5º: após isso, será retornado a valoração para executar o caminho euleriano no grafo.


