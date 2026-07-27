---
title: "Aspose::Slides::MathText"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 157
url: /pt/aspose.slides.mathtext/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [BaseScript](./basescript/) | script de matemática |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) com [Control](../aspose.slides/control/) Propriedades de Caractere |
| [IMathAccent](./imathaccent/) | Especifica a função de acento, consistindo em uma base e um sinal diacrítico combinante. Exemplo: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Permite criar um acento matemático |
| [IMathArray](./imatharray/) | Especifica uma matriz vertical de equações ou quaisquer objetos matemáticos |
| [IMathArrayFactory](./imatharrayfactory/) | Permite criar uma matriz matemática |
| [IMathBar](./imathbar/) | Especifica a função barra, consistindo em um argumento base e uma barra superior ou inferior |
| [IMathBarFactory](./imathbarfactory/) | Permite criar uma barra matemática |
| [IMathBlock](./imathblock/) | Especifica uma instância de texto matemático que está contido dentro de um [MathParagraph](./mathparagraph/) e começa em sua própria linha. Todas as zonas de matemática, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas são representadas por bloco matemático. |
| [IMathBlockCollection](./imathblockcollection/) | Coleção de blocos matemáticos ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Permite criar um bloco matemático |
| [IMathBorderBox](./imathborderbox/) | Desenha um contorno retangular ou outro tipo de borda ao redor do [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Permite criar uma caixa de borda matemática |
| [IMathBox](./imathbox/) | Especifica a embalagem lógica (boxing) de elemento matemático. Por exemplo, um objeto em caixa pode servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro dele. Por exemplo, o operador \"==\" deve ser colocado em caixa para impedir quebras de linha. |
| [IMathBoxFactory](./imathboxfactory/) | Permite criar uma caixa matemática |
| [IMathDelimiter](./imathdelimiter/) | Especifica o objeto delimitador, consistindo em caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Permite criar um delimitador matemático |
| [IMathElement](./imathelement/) | Interface base de qualquer elemento matemático: fração, texto matemático, função, expressão com múltiplos elementos etc |
| [IMathElementCollection](./imathelementcollection/) | Representa uma coleção de elementos matemáticos (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Texto matemático |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Permite criar um elemento [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Especifica o objeto fração, consistindo em um numerador e denominador separados por uma barra de fração. A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração. O objeto fração também é usado para representar a função pilha, que coloca um elemento acima de outro, sem barra de fração. |
| [IMathFractionFactory](./imathfractionfactory/) | Permite criar uma fração matemática |
| [IMathFunction](./imathfunction/) | Especifica uma função de um argumento. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Permite criar uma função matemática |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, geralmente para destacar a relação entre os elementos |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Permite criar um caractere de agrupamento matemático |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Especifica o objeto Sub-Superscript, que consiste em uma base e um subscript e superscript posicionados à esquerda da base. |
| [IMathLimit](./imathlimit/) | Especifica o objeto Limit, consistindo em texto na linha de base e texto de tamanho reduzido imediatamente acima ou abaixo dele. |
| [IMathLimitFactory](./imathlimitfactory/) | Permite criar [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Especifica o objeto Matrix, consistindo em elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores embutidos. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador ([IMathDelimiter](./imathdelimiter/)). Argumentos nulos podem ser usados para criar lacunas nas matrizes. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Permite criar uma matriz matemática |
| [IMathNaryOperator](./imathnaryoperator/) | Especifica um objeto matemático N-ário, como Somatório e Integral. Consiste em um operador, uma base (ou operando), e limites superiores e inferiores opcionais. Exemplos de operadores N-ários são: Somatório, União, Interseção, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Permite criar [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Especifica propriedades de [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Parágrafo matemático que é um contêiner para blocos matemáticos ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Permite criar um parágrafo matemático |
| [IMathPhantom](./imathphantom/) | Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho sem necessariamente exibí-lo. Um fantasma pode ocultar sua expressão base mantendo sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. Visibilidade e comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [IMathPortion](./imathportion/) | Representa uma porção com contexto matemático interno. |
| [IMathRadical](./imathradical/) | Especifica a função radical, consistindo em uma base e um grau opcional. Exemplo de objeto radical é \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Permite criar radical matemático |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Especifica o objeto Sub-Superscript, que consiste em uma base e um subscript e superscript posicionados à direita da base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Permite criar [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Especifica o objeto subscript, que consiste em uma base e um subscript de tamanho reduzido posicionado abaixo e à direita. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Permite criar [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Especifica o objeto superscript, que consiste em uma base e um superscript de tamanho reduzido posicionado acima e à direita |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Permite criar [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Especifica a função de acento, consistindo em uma base e um sinal diacrítico combinante. Exemplo: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Permite criar um acento matemático |
| [MathArray](./matharray/) | Especifica uma matriz vertical de equações ou quaisquer objetos matemáticos |
| [MathArrayFactory](./matharrayfactory/) | Permite criar uma matriz matemática |
| [MathBar](./mathbar/) | Especifica a função barra, consistindo em um argumento base e uma barra superior ou inferior |
| [MathBarFactory](./mathbarfactory/) | Permite criar uma barra matemática |
| [MathBlock](./mathblock/) | Especifica uma instância de texto matemático que está contida dentro de um [MathParagraph](./mathparagraph/) e começa em sua própria linha. Todas as zonas de matemática, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas são representadas por bloco matemático. |
| [MathBlockFactory](./mathblockfactory/) | Permite criar um bloco matemático |
| [MathBorderBox](./mathborderbox/) | Desenha um contorno retangular ou outro tipo de borda ao redor do [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Permite criar uma caixa de borda matemática |
| [MathBox](./mathbox/) | Especifica a embalagem lógica (boxing) de elemento matemático. Por exemplo, um objeto em caixa pode servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro dele. Por exemplo, o operador \"==\" deve ser colocado em caixa para impedir quebras de linha. |
| [MathBoxFactory](./mathboxfactory/) | Permite criar uma caixa matemática |
| [MathDelimiter](./mathdelimiter/) | Especifica o objeto delimitador, consistindo em caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado. Exemplos: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Permite criar um delimitador matemático |
| [MathElementBase](./mathelementbase/) | Classe base para [IMathElement](./imathelement/) com a implementação de alguns métodos que são comuns a todas as classes herdadas. Apenas para uso interno. A classe herdada deve ser [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Texto matemático |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Permite criar um elemento [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Especifica o objeto fração, consistindo em um numerador e denominador separados por uma barra de fração. A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração. O objeto fração também é usado para representar a função pilha, que coloca um elemento acima de outro, sem barra de fração. |
| [MathFractionFactory](./mathfractionfactory/) | Permite criar uma fração matemática |
| [MathFunction](./mathfunction/) | Especifica uma função de um argumento. |
| [MathFunctionFactory](./mathfunctionfactory/) | Permite criar uma função matemática |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, geralmente para destacar a relação entre os elementos |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Permite criar um caractere de agrupamento matemático |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Especifica o objeto Sub-Superscript, que consiste em uma base e um subscript e superscript posicionados à esquerda da base. |
| [MathLimit](./mathlimit/) | Especifica o objeto Limit, consistindo em texto na linha de base e texto de tamanho reduzido imediatamente acima ou abaixo dele. |
| [MathLimitFactory](./mathlimitfactory/) | Permite criar [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Especifica o objeto Matrix, consistindo em elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores embutidos. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador ([IMathDelimiter](./imathdelimiter/)). Argumentos nulos podem ser usados para criar lacunas nas matrizes. |
| [MathMatrixFactory](./mathmatrixfactory/) | Permite criar uma matriz matemática |
| [MathNaryOperator](./mathnaryoperator/) | Especifica um objeto matemático N-ário, como Somatório e Integral. Consiste em um operador, uma base (ou operando), e limites superiores e inferiores opcionais. Exemplos de operadores N-ários são: Somatório, União, Interseção, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Permite criar [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Parágrafo matemático que é um contêiner para blocos matemáticos ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Permite criar um parágrafo matemático |
| [MathPhantom](./mathphantom/) | Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho sem necessariamente exibí-lo. Um fantasma pode ocultar sua expressão base mantendo sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. Visibilidade e comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [MathPortion](./mathportion/) | Representa uma porção com contexto matemático interno. |
| [MathRadical](./mathradical/) | Especifica a função radical, consistindo em uma base e um grau opcional. Exemplo de objeto radical é \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Permite criar radical matemático |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Especifica o objeto Sub-Superscript, que consiste em uma base e um subscript e superscript posicionados à direita da base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Permite criar [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Especifica o objeto subscript, que consiste em uma base e um subscript de tamanho reduzido posicionado abaixo e à direita. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Permite criar [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Especifica o objeto superscript, que consiste em uma base e um superscript de tamanho reduzido posicionado acima e à direita |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Permite criar [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Enumerações

| Enum | Descrição |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | A localização e o tamanho dos delimitadores em relação ao conteúdo dos operandos |
| [MathFractionTypes](./mathfractiontypes/) | Tipos de Fração |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Funções matemáticas comuns de um argumento |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Funções matemáticas comuns de dois argumentos |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Alinhamento Horizontal |
| [MathIntegralTypes](./mathintegraltypes/) | Tipos de integrais matemáticas |
| [MathJustification](./mathjustification/) | Especifica a justificativa do parágrafo matemático (uma série de instâncias adjacentes de texto matemático dentro do mesmo parágrafo) |
| [MathLimitLocations](./mathlimitlocations/) | Localização dos limites (subscript/superscript) em operadores n-ários. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Tipos de operador n-ário [IMathNaryOperator](./imathnaryoperator/) (excluindo integrais) Para integrais [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | O tipo de espaçamento vertical entre colunas em uma matriz ou array |
| [MathSpacingRules](./mathspacingrules/) | Tipos de espaçamento (horizontal) entre colunas de uma matriz |
| [MathTopBotPositions](./mathtopbotpositions/) | Enumeração de posições superior/inferior |
| [MathVerticalAlignment](./mathverticalalignment/) | Alinhamento Vertical |