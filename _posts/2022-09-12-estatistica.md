# Análise Estatística

A correta análise estatística dos dados é muito importante nos ensaios clínicos. Surpreendentemente, entretanto, as análises estatísticas realizadas são frequentemente omitidas dos ensaios clínicos e outros artigos publicados [@baharUseMisuseStatistical2019].
O tamanho da amostra é importante,  já que amostras pequenas tendem a mostrar mais diferenças significativas entre os grupos de tratamento. Além disso, a quantidade e as características dos dados são de extrema importância para a escolha dos testes estatísticos corretos.



## Entendendo *p*

A compreensão do significado de *p* é fundamental para entender e interpretar testes estatísticos.
Em termos simples, todos os ensaios clínicos começam com a hipótese nula de que os tratamentos são equivalentes. Se os resultados do ensaio indicam que os resultados são diferentes, então um teste estatístico é realizado para verificar se a diferença é devida ao acaso. Se o acaso não for uma explicação provável para a diferença, a hipótese nula de que os tratamentos são equivalentes é rejeitada.

O valor de *p* representa a probabilidade de que uma diferença tão grande quanto a observada pode ser devida ao acaso e de que os tratamentos são na verdade equivalentes.

O erro de acreditar que existe uma diferença entre os tratamentos, quando na verdade essa diferença não existe e as diferenças observadas são devidas ao acaso, é chamado de erro tipo I ou erro alfa.

 **A diferença foi estatisticamente significativa (*p*= 0,05)** significa que a probabilidade de que uma diferença tão grande quanto a observada seja devida ao acaso é de 1 em 20 *e* que o autor aceita esse nível de probabilidade como suficientemente improvável e por isso rejeita a hipótese nula de que os tratamentos são equivalentes.
 
Inversamente, a frase **a diferença não foi estatisticamente significativa (*p*=0,10)** significa que a probabilidade de que uma diferença tão grande quanto a observada seja devida ao acaso é de 1 em 10 e que o autor não considera esse nível de probabilidade como suficientemente improvável para rejeitar a hipótese nula de que os tratamentos são equivalentes.

É importante lembrar que **não significativo** significa que  uma diferença *não foi provada*; não significa que não exista diferença.

 A aceitação de um nível de significância de 0,05 como o limite para rejeitar a hipótese nula é uma tradição baseada em padrões de controle de qualidade e não é uma verdade absoluta [@bigbyUnderstandingEvaluatingClinical1996].
Os autores devem indicar os testes estatísticos que foram utilizados para comparar os resultados. Dizer apenas que a diferença foi estatisticamente significativa (*p* < 0,050) não constitui uma descrição adequada da estatística utilizada.



## O Teste *t*

O teste *t* é o teste mais comumente utilizado na literatura biomédica, e é usado para determinar se a diferença entre as médias de duas amostras é devida apenas ao acaso.
É importante lembrar que o  teste *t* a um nível de significância de 0,05 é desenhado para comparar as diferenças nas médias de apenas **duas** amostras ou populações.

#### Outras limitações do teste *t*

O teste *t* deve ser usado para comparar as médias de dados que têm uma distribuição normal. 
Além disso, ele tem também as seguintes limitações:

1. os dados analisados pelo teste *t* devem ser de tamanho suficiente;
1. não devem conter *outliers*;
1. a variabilidade (desvio-padrão) dos dois grupos de tratamento deve ser similar;
1. na maioria dos casos, um teste *t* bilateral é apropriado;
1. quando se utiliza um teste *t* unilateral, as razões devem ser especificadas;
1. o teste *t* pareado deve ser utilizado para analisar os efeitos de dois tratamentos nos mesmos pacientes (estudo *crossover*).



#### Erros comuns no uso do teste *t*

Sendo o teste estatístico mais comumente empregado, não é surpreendente que ele seja também frequentemente utilizado de modo inadequado. 
Os erros mais comuns são utilizá-lo para analisar:

1. dados sem distribuição normal;
1. dados com variabilidades diferentes nas amostras;
1. dados pareados por meio do  teste *t* não-pareado;
1. as médias de _mais de duas_ amostras.

O teste *t* não deve ser utilizado para analisar dados que apresentam variabilidade (desvio-padrão) muito diferente entre os grupos de tratamento. 
Também não deve ser usado com conjuntos de dados muito pequenos porque é impossível verificar a normalidade da sua distribuição. Nesses casos, pode ser usado o _teste U de Mann-Whitney_, que é o equivalente ao teste *t* para distribuições não normais e dados não pareados. Para dados pareados, pode ser usado o _teste de Wilcoxon_.
 Os testes de médias *para mais de dois grupos*  podem ser realizados com diferentes formas de _análise de variância_.


## Qui-quadrado

É o teste mais utilizado para analisar dados categóricos (ex.: boa resposta/sem resposta ao tratamento).
Entretanto, para conjuntos pequenos de dados (20-40 pacientes) deve ser usada a correção de Yates e o qui-quadrado não deve ser usado para analisar ensaios com menos de 20 pacientes ou quando o número de pacientes em qualquer das categorias for menor do que 5. Nesses casos, deve ser usado o *teste exato de Fisher*.
O teste Qui-quadrado é usado para analisar dados categóricos não pareados e o  _teste de McNemar_  é usado para _dados pareados_.

As tabelas de contingência podem ser facilmente modificadas para comparar mais de dois tratamentos ou mais de dois desfechos.

![Exemplo de tabela de contingência, cálculo do qui-quadrado e da correção de Yates (Bigby and Gadenne, 1996).](conttable.png "Exemplo de tabela de contingência, cálculo do qui-quadrado e da correção de Yates (Bigby and Gadenne, 1996).")

 Assim como o teste *t*, o qui-quadrado é frequentemente usado de modo incorreto em ensaios clínicos publicados.

Gore, Jones e Ritter [@goreMisuseStatisticalMethods1977], numa análise de artigos publicados no *British Medical Journal* verificaram uso incorreto do teste qui-quadrado em 12 de 62 trabalhos!


### Erros comuns no uso do teste Qui-Quadrado

Os erros mais comuns em relação ao qui-quadrado são:

1. falha de usar a correção de Yates para amostras pequenas;
1. omissão de uma hipótese clara a ser testada;
1. falta de consideração dos graus de liberdade;
1. uso incorreto do teste para estudar dados pareados.


# Conclusão

 Ao analisarmos a qualidade de um ensaio clínico publicado, devemos estar atentos ao uso correto das análises estatísticas e à sua interpretação adequada.
 

# Referências













