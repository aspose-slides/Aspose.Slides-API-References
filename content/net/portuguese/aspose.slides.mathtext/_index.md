---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes para Referência de API .NET
description: Contém classes para trabalhar com texto matemático em apresentações do Microsoft PowerPoint.
type: docs
weight: 140
url: /pt/aspose.slides.mathtext/
---
Contém classes para trabalhar com texto matemático em apresentações do Microsoft PowerPoint.

## Classes

| Classe | Descrição |
| --- | --- |
| [BaseScript](./basescript) | Script matemático |
| [MathAccent](./mathaccent) | Especifica a função acento, consistindo de uma base e um sinal diacrítico combinável. Exemplo: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Permite criar um acento matemático |
| [MathArray](./matharray) | Especifica um arranjo vertical de equações ou quaisquer objetos matemáticos |
| [MathArrayFactory](./matharrayfactory) | Permite criar um arranjo matemático |
| [MathBar](./mathbar) | Especifica a função barra, consistindo de um argumento base e uma barra superior ou inferior |
| [MathBarFactory](./mathbarfactory) | Permite criar uma barra matemática |
| [MathBlock](./mathblock) | Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha. Todas as zonas matemáticas, incluindo equações, expressões, arranjos de equações ou expressões e fórmulas são representadas por um bloco matemático. |
| [MathBlockFactory](./mathblockfactory) | Permite criar um bloco matemático |
| [MathBorderBox](./mathborderbox) | Desenha um contorno retangular ou outro tipo de borda ao redor do IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Permite criar uma caixa de borda matemática |
| [MathBox](./mathbox) | Especifica o empacotamento lógico (boxing) de elemento matemático. Por exemplo, um objeto encapsulado pode servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha dentro dele. Por exemplo, o operador "==" deve ser encapsulado para evitar quebras de linha. |
| [MathBoxFactory](./mathboxfactory) | Permite criar uma caixa matemática |
| [MathDelimiter](./mathdelimiter) | Especifica o objeto delimitador, consistindo de caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Permite criar um delimitador matemático |
| [MathElementBase](./mathelementbase) | Classe base para IMathElement com a implementação de alguns métodos que são comuns a todas as classes herdadas. Uso interno somente. A classe herdada deve ser IMathElement. |
| [MathematicalText](./mathematicaltext) | Texto matemático |
| [MathematicalTextFactory](./mathematicaltextfactory) | Permite criar um elemento MathematicalText |
| [MathFraction](./mathfraction) | Especifica o objeto fração, consistindo de um numerador e um denominador separados por uma barra de fração. A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração. O objeto fração também é usado para representar a função pilha, que coloca um elemento acima de outro, sem barra de fração. |
| [MathFractionFactory](./mathfractionfactory) | Permite criar uma fração matemática |
| [MathFunction](./mathfunction) | Especifica uma função de um argumento. |
| [MathFunctionFactory](./mathfunctionfactory) | Permite criar uma função matemática |
| [MathGroupingCharacter](./mathgroupingcharacter) | Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, geralmente para destacar a relação entre os elementos. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Permite criar um caractere de agrupamento matemático |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base e um subscrito e sobrescrito posicionados à esquerda da base. |
| [MathLimit](./mathlimit) | Especifica o objeto Limite, consistindo de texto na linha de base e texto de tamanho reduzido imediatamente acima ou abaixo dele. |
| [MathLimitFactory](./mathlimitfactory) | Permite criar IMathLimit |
| [MathMatrix](./mathmatrix) | Especifica o objeto Matriz, consistindo de elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores embutidos. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas nas matrizes. |
| [MathMatrixFactory](./mathmatrixfactory) | Permite criar uma matriz matemática |
| [MathNaryOperator](./mathnaryoperator) | Especifica um objeto matemático N-ário, como Summation e Integral. Consiste em um operador, uma base (ou operando) e limites superiores e inferiores opcionais. Exemplos de operadores N-ários são: Summation, Union, Intersection, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Permite criar IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Parágrafo matemático que é um contêiner para blocos matemáticos (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Permite criar um parágrafo matemático |
| [MathPhantom](./mathphantom) | Representa um objeto matemático fantasma (&lt;m:phant&gt;) que afeta o layout de seu elemento filho sem necessariamente exibi-lo. Um fantasma pode ocultar sua expressão base enquanto preserva sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. A visibilidade e o comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [MathPortion](./mathportion) | Representa uma porção com contexto matemático interno. |
| [MathRadical](./mathradical) | Especifica a função radical, consistindo de uma base e um grau opcional. Exemplo de objeto radical é √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Permite criar um radical matemático |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base e um subscrito e sobrescrito posicionados à direita da base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Permite criar IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Especifica o objeto subscrito, que consiste em uma base e um subscrito de tamanho reduzido posicionado abaixo e à direita. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Permite criar IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Especifica o objeto sobrescrito, que consiste em uma base e um sobrescrito de tamanho reduzido posicionado acima e à direita |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Permite criar IMathSuperscriptElement |

## Interfaces

| Interface | Descrição |
| --- | --- |
| [IMathAccent](./imathaccent) | Especifica a função acento, consistindo de uma base e um sinal diacrítico combinável. Exemplo: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Permite criar um acento matemático |
| [IMathArray](./imatharray) | Especifica um arranjo vertical de equações ou quaisquer objetos matemáticos |
| [IMathArrayFactory](./imatharrayfactory) | Permite criar um arranjo matemático |
| [IMathBar](./imathbar) | Especifica a função barra, consistindo de um argumento base e uma barra superior ou inferior |
| [IMathBarFactory](./imathbarfactory) | Permite criar uma barra matemática |
| [IMathBlock](./imathblock) | Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha. Todas as zonas matemáticas, incluindo equações, expressões, arranjos de equações ou expressões e fórmulas são representadas por um bloco matemático. |
| [IMathBlockCollection](./imathblockcollection) | Coleção de blocos matemáticos (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Permite criar um bloco matemático |
| [IMathBorderBox](./imathborderbox) | Desenha um contorno retangular ou outro tipo de borda ao redor do IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Permite criar uma caixa de borda matemática |
| [IMathBox](./imathbox) | Especifica o empacotamento lógico (boxing) de elemento matemático. Por exemplo, um objeto encapsulado pode servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha dentro dele. Por exemplo, o operador "==" deve ser encapsulado para evitar quebras de linha. |
| [IMathBoxFactory](./imathboxfactory) | Permite criar uma caixa matemática |
| [IMathDelimiter](./imathdelimiter) | Especifica o objeto delimitador, consistindo de caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Permite criar um delimitador matemático |
| [IMathElement](./imathelement) | Interface base de qualquer elemento matemático: fração, texto matemático, função, expressão com múltiplos elementos etc |
| [IMathElementCollection](./imathelementcollection) | Representa uma coleção de elementos matemáticos (MathElement). |
| [IMathematicalText](./imathematicaltext) | Texto matemático |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Permite criar um elemento MathematicalText |
| [IMathFraction](./imathfraction) | Especifica o objeto fração, consistindo de um numerador e um denominador separados por uma barra de fração. A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração. O objeto fração também é usado para representar a função pilha, que coloca um elemento acima de outro, sem barra de fração. |
| [IMathFractionFactory](./imathfractionfactory) | Permite criar uma fração matemática |
| [IMathFunction](./imathfunction) | Especifica uma função de um argumento. |
| [IMathFunctionFactory](./imathfunctionfactory) | Permite criar uma função matemática |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, geralmente para destacar a relação entre os elementos. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Permite criar um caractere de agrupamento matemático |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base e um subscrito e sobrescrito posicionados à esquerda da base. |
| [IMathLimit](./imathlimit) | Especifica o objeto Limite, consistindo de texto na linha de base e texto de tamanho reduzido imediatamente acima ou abaixo dele. |
| [IMathLimitFactory](./imathlimitfactory) | Permite criar IMathLimit |
| [IMathMatrix](./imathmatrix) | Especifica o objeto Matriz, consistindo de elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores embutidos. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas nas matrizes. |
| [IMathMatrixFactory](./imathmatrixfactory) | Permite criar uma matriz matemática |
| [IMathNaryOperator](./imathnaryoperator) | Especifica um objeto matemático N-ário, como Summation e Integral. Consiste em um operador, uma base (ou operando) e limites superiores e inferiores opcionais. Exemplos de operadores N-ários são: Summation, Union, Intersection, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Permite criar IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Especifica propriedades de IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Parágrafo matemático que é um contêiner para blocos matemáticos (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Permite criar um parágrafo matemático |
| [IMathPhantom](./imathphantom) | Representa um objeto matemático fantasma (&lt;m:phant&gt;) que afeta o layout de seu elemento filho sem necessariamente exibi-lo. Um fantasma pode ocultar sua expressão base enquanto preserva sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. A visibilidade e o comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [IMathPortion](./imathportion) | Representa uma porção com contexto matemático interno. |
| [IMathRadical](./imathradical) | Especifica a função radical, consistindo de uma base e um grau opcional. Exemplo de objeto radical é √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Permite criar um radical matemático |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base e um subscrito e sobrescrito posicionados à direita da base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Permite criar IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Especifica o objeto subscrito, que consiste em uma base e um subscrito de tamanho reduzido posicionado abaixo e à direita. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Permite criar IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Especifica o objeto sobrescrito, que consiste em uma base e um sobrescrito de tamanho reduzido posicionado acima e à direita |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Permite criar IMathSuperscriptElement |

## Enumeração

| Enumeração | Descrição |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | A localização e o tamanho dos delimitadores em relação ao conteúdo dos operandos |
| [MathFractionTypes](./mathfractiontypes) | Tipos de Fração |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Funções matemáticas comuns de um argumento |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Funções matemáticas comuns de dois argumentos |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Alinhamento Horizontal |
| [MathIntegralTypes](./mathintegraltypes) | Tipos de integrais matemáticas |
| [MathJustification](./mathjustification) | Especifica a justificação do parágrafo matemático (uma série de instâncias adjacentes de texto matemático dentro do mesmo parágrafo) |
| [MathLimitLocations](./mathlimitlocations) | Localização dos limites (subscrito/sobrescrito) em operadores n-ários. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Tipos de operadores n-ários IMathNaryOperator (excluindo integrais) Para integrais [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | O tipo de espaçamento vertical entre colunas em uma matriz ou arranjo |
| [MathSpacingRules](./mathspacingrules) | Tipos de espaço (espaçamento horizontal) entre colunas de uma matriz |
| [MathTopBotPositions](./mathtopbotpositions) | Enumeração de posições superior/inferior |
| [MathVerticalAlignment](./mathverticalalignment) | Alinhamento Vertical |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->