Padroes de Projeto

1) Criacionais -> Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.
2) Estruturais -> Os padrões estruturais explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
3) Comportamentais -> Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos.

* Estruturais

3.Composite

O que é:
O Composite é um padrão de projeto estrutural que permite que você componha objetos em estruturas de árvores e então trabalhe com essas estruturas como se elas fossem objetos individuais.

Aplicabilidade:
Utilize o padrão Composite quando você tem que implementar uma estrutura de objetos tipo árvore.
Utilize o padrão quando você quer que o código cliente trate tanto os objetos simples como os compostos de forma uniforme.

Identificação:
É fácil reconhecer o Composite por métodos comportamentais, levando uma instância do mesmo tipo abstrato/interface para uma estrutura em árvore.

Exempos de utilizacao:
java.awt.Container#add(Component)