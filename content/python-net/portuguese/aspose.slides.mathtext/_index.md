---
title: aspose.slides.mathtext
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.mathtext/
---
Contém classes para trabalhar com texto matemático em apresentações do Microsoft PowerPoint.
## Classes

| Classe | Descrição |
| :- | :- |
| [`BaseScript`](/slides/python-net/pt/aspose.slides.mathtext/basescript/) | Script matemático |
| [`IMathAccent`](/slides/python-net/pt/aspose.slides.mathtext/imathaccent/) | Especifica a função de acento, composta por uma base e uma marca diacrítica combinada<br/>            Exemplo: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathaccentfactory/) | Permite criar um acento matemático |
| [`IMathArray`](/slides/python-net/pt/aspose.slides.mathtext/imatharray/) | Especifica um vetor vertical de equações ou quaisquer objetos matemáticos |
| [`IMathArrayFactory`](/slides/python-net/pt/aspose.slides.mathtext/imatharrayfactory/) | Permite criar um array matemático |
| [`IMathBar`](/slides/python-net/pt/aspose.slides.mathtext/imathbar/) | Especifica a função barra, composta por um argumento base e uma barra superior ou inferior |
| [`IMathBarFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathbarfactory/) | Permite criar uma barra matemática |
| [`IMathBlock`](/slides/python-net/pt/aspose.slides.mathtext/imathblock/) | Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha.<br/>            Todas as zonas matemáticas, incluindo equações, expressões, arrays de equações ou expressões e fórmulas são representadas por bloco matemático. |
| [`IMathBlockCollection`](/slides/python-net/pt/aspose.slides.mathtext/imathblockcollection/) | Coleção de blocos matemáticos (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathblockfactory/) | Permite criar um bloco matemático |
| [`IMathBorderBox`](/slides/python-net/pt/aspose.slides.mathtext/imathborderbox/) | Desenha um contorno retangular ou outro contorno ao redor do IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathborderboxfactory/) | Permite criar uma caixa de borda matemática |
| [`IMathBox`](/slides/python-net/pt/aspose.slides.mathtext/imathbox/) | Especifica o empacotamento lógico (boxing) de elemento matemático.<br/>            Por exemplo, um objeto empacotado pode servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha internas.<br/>            Por exemplo, o operador \"==\" deve ser empacotado para evitar quebras de linha. |
| [`IMathBoxFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathboxfactory/) | Permite criar uma caixa matemática |
| [`IMathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiter/) | Especifica o objeto delimitador, composto por caracteres de abertura e fechamento (como parênteses, <br/>            chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado.<br/>            Exemplos: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiterfactory/) | Permite criar um delimitador matemático |
| [`IMathElement`](/slides/python-net/pt/aspose.slides.mathtext/imathelement/) | Interface base de qualquer elemento matemático: <br/>            fração, texto matemático, função, expressão com múltiplos elementos etc |
| [`IMathElementCollection`](/slides/python-net/pt/aspose.slides.mathtext/imathelementcollection/) | Representa uma coleção de elementos matemáticos (MathElement). |
| [`IMathFraction`](/slides/python-net/pt/aspose.slides.mathtext/imathfraction/) | Especifica o objeto fração, composto por um numerador e denominador separados por uma barra de fração.<br/>            A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração.<br/>            O objeto fração também é usado para representar a função empilhamento, que coloca um elemento acima do outro, sem barra de fração. |
| [`IMathFractionFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathfractionfactory/) | Permite criar uma fração matemática |
| [`IMathFunction`](/slides/python-net/pt/aspose.slides.mathtext/imathfunction/) | Especifica uma função de um argumento. |
| [`IMathFunctionFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathfunctionfactory/) | Permite criar uma função matemática |
| [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter/) | Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, geralmente para destacar a relação entre os elementos. |
| [`IMathGroupingCharacterFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Permite criar um caractere de agrupamento matemático |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base <br/>            e um subíndice e sobrescrito posicionados à esquerda da base. |
| [`IMathLimit`](/slides/python-net/pt/aspose.slides.mathtext/imathlimit/) | Especifica o objeto Limite, composto por texto na linha de base e texto de tamanho reduzido imediatamente acima ou abaixo dele. |
| [`IMathLimitFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathlimitfactory/) | Permite criar IMathLimit |
| [`IMathMatrix`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/) | Especifica o objeto Matriz, composto por elementos filhos organizados em uma ou mais linhas e colunas. <br/>            É importante observar que matrizes não possuem delimitadores incorporados. <br/>            Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter).<br/>            Argumentos nulos podem ser usados para criar lacunas nas matrizes. |
| [`IMathMatrixFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrixfactory/) | Permite criar uma matriz matemática |
| [`IMathNaryOperator`](/slides/python-net/pt/aspose.slides.mathtext/imathnaryoperator/) | Especifica um objeto matemático N-ário, como Summation e Integral.<br/>            Consiste em um operador, uma base (ou operando), e limites superior e inferior opcionais. <br/>            Exemplos de operadores N-ários são: Summation, Union, Intersection, Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathnaryoperatorfactory/) | Permite criar IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/pt/aspose.slides.mathtext/imathnaryoperatorproperties/) | Especifica propriedades de IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/pt/aspose.slides.mathtext/imathparagraph/) | Parágrafo matemático que é um contêiner para blocos matemáticos (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathparagraphfactory/) | Permite criar um parágrafo matemático |
| [`IMathPhantom`](/slides/python-net/pt/aspose.slides.mathtext/imathphantom/) | Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho<br/>            sem necessariamente exibi-lo. Um fantasma pode ocultar sua expressão base enquanto preserva<br/>            sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. <br/>            Visibilidade e comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc e Transp. |
| [`IMathPortion`](/slides/python-net/pt/aspose.slides.mathtext/imathportion/) | Representa uma porção com contexto matemático interno. |
| [`IMathRadical`](/slides/python-net/pt/aspose.slides.mathtext/imathradical/) | Especifica a função radical, composta por uma base e um grau opcional.<br/>            Exemplo de objeto radical é √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathradicalfactory/) | Permite criar radical matemático |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base <br/>            e um subíndice e sobrescrito posicionados à direita da base. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Permite criar IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/imathsubscriptelement/) | Especifica o objeto subscrito, que consiste em uma base <br/>            e um subscrito de tamanho reduzido posicionado abaixo e à direita. |
| [`IMathSubscriptElementFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathsubscriptelementfactory/) | Permite criar IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/imathsuperscriptelement/) | Especifica o objeto sobrescrito, que consiste em uma base <br/>            e um sobrescrito de tamanho reduzido posicionado acima e à direita |
| [`IMathSuperscriptElementFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Permite criar IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/pt/aspose.slides.mathtext/imathematicaltext/) | Texto matemático |
| [`IMathematicalTextFactory`](/slides/python-net/pt/aspose.slides.mathtext/imathematicaltextfactory/) | Permite criar um elemento MathematicalText |
| [`MathAccent`](/slides/python-net/pt/aspose.slides.mathtext/mathaccent/) | Especifica a função de acento, composta por uma base e uma marca diacrítica combinada<br/>            Exemplo: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathaccentfactory/) | Permite criar um acento matemático |
| [`MathArray`](/slides/python-net/pt/aspose.slides.mathtext/matharray/) | Especifica um vetor vertical de equações ou quaisquer objetos matemáticos |
| [`MathArrayFactory`](/slides/python-net/pt/aspose.slides.mathtext/matharrayfactory/) | Permite criar um array matemático |
| [`MathBar`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/) | Especifica a função barra, composta por um argumento base e uma barra superior ou inferior |
| [`MathBarFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathbarfactory/) | Permite criar uma barra matemática |
| [`MathBlock`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/) | Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha.<br/>            Todas as zonas matemáticas, incluindo equações, expressões, arrays de equações ou expressões e fórmulas são representadas por bloco matemático. |
| [`MathBlockFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathblockfactory/) | Permite criar um bloco matemático |
| [`MathBorderBox`](/slides/python-net/pt/aspose.slides.mathtext/mathborderbox/) | Desenha um contorno retangular ou outro contorno ao redor do IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathborderboxfactory/) | Permite criar uma caixa de borda matemática |
| [`MathBox`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/) | Especifica o empacotamento lógico (boxing) de elemento matemático.<br/>            Por exemplo, um objeto empacotado pode servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha internas.<br/>            Por exemplo, o operador \"==\" deve ser empacotado para evitar quebras de linha. |
| [`MathBoxFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathboxfactory/) | Permite criar uma caixa matemática |
| [`MathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/mathdelimiter/) | Especifica o objeto delimitador, composto por caracteres de abertura e fechamento (como parênteses, <br/>            chaves, colchetes e barras verticais), e um ou mais elementos matemáticos dentro, separados por um caractere especificado.<br/>            Exemplos: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathdelimiterfactory/) | Permite criar um delimitador matemático |
| [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase/) | Classe base para IMathElement com a implementação de alguns métodos comuns a todas as classes herdadas<br/>            Uso interno apenas. A classe herdada deve ser IMathElement. |
| [`MathFraction`](/slides/python-net/pt/aspose.slides.mathtext/mathfraction/) | Especifica o objeto fração, composto por um numerador e denominador separados por uma barra de fração.<br/>            A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração.<br/>            O objeto fração também é usado para representar a função empilhamento, que coloca um elemento acima do outro, sem barra de fração. |
| [`MathFractionFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathfractionfactory/) | Permite criar uma fração matemática |
| [`MathFunction`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/) | Especifica uma função de um argumento. |
| [`MathFunctionFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathfunctionfactory/) | Permite criar uma função matemática |
| [`MathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/) | Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, geralmente para destacar a relação entre os elementos. |
| [`MathGroupingCharacterFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Permite criar um caractere de agrupamento matemático |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base <br/>            e um subíndice e sobrescrito posicionados à esquerda da base. |
| [`MathLimit`](/slides/python-net/pt/aspose.slides.mathtext/mathlimit/) | Especifica o objeto Limite, composto por texto na linha de base e texto de tamanho reduzido imediatamente acima ou abaixo dele. |
| [`MathLimitFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathlimitfactory/) | Permite criar IMathLimit |
| [`MathMatrix`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/) | Especifica o objeto Matriz, composto por elementos filhos organizados em uma ou mais linhas e colunas. <br/>            É importante observar que matrizes não possuem delimitadores incorporados. <br/>            Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter).<br/>            Argumentos nulos podem ser usados para criar lacunas nas matrizes. |
| [`MathMatrixFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrixfactory/) | Permite criar uma matriz matemática |
| [`MathNaryOperator`](/slides/python-net/pt/aspose.slides.mathtext/mathnaryoperator/) | Especifica um objeto matemático N-ário, como Summation e Integral.<br/>            Consiste em um operador, uma base (ou operando), e limites superior e inferior opcionais. <br/>            Exemplos de operadores N-ários são: Summation, Union, Intersection, Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathnaryoperatorfactory/) | Permite criar IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/pt/aspose.slides.mathtext/mathparagraph/) | Parágrafo matemático que é um contêiner para blocos matemáticos (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathparagraphfactory/) | Permite criar um parágrafo matemático |
| [`MathPhantom`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/) | Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho<br/>            sem necessariamente exibi-lo. Um fantasma pode ocultar sua expressão base enquanto preserva<br/>            sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. <br/>            Visibilidade e comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc e Transp. |
| [`MathPortion`](/slides/python-net/pt/aspose.slides.mathtext/mathportion/) | Representa uma porção com contexto matemático interno. |
| [`MathRadical`](/slides/python-net/pt/aspose.slides.mathtext/mathradical/) | Especifica a função radical, composta por uma base e um grau opcional.<br/>            Exemplo de objeto radical é √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathradicalfactory/) | Permite criar radical matemático |
| [`MathRightSubSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Especifica o objeto Sub-Sobrescrito, que consiste em uma base <br/>            e um subíndice e sobrescrito posicionados à direita da base. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Permite criar IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/mathsubscriptelement/) | Especifica o objeto subscrito, que consiste em uma base <br/>            e um subscrito de tamanho reduzido posicionado abaixo e à direita. |
| [`MathSubscriptElementFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathsubscriptelementfactory/) | Permite criar IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/) | Especifica o objeto sobrescrito, que consiste em uma base <br/>            e um sobrescrito de tamanho reduzido posicionado acima e à direita |
| [`MathSuperscriptElementFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Permite criar IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/pt/aspose.slides.mathtext/mathematicaltext/) | Texto matemático |
| [`MathematicalTextFactory`](/slides/python-net/pt/aspose.slides.mathtext/mathematicaltextfactory/) | Permite criar um elemento MathematicalText |

## Enumerações

| Enumeração | Descrição |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/pt/aspose.slides.mathtext/mathdelimitershape/) | A localização e o tamanho dos delimitadores em relação ao conteúdo dos operandos |
| [`MathFractionTypes`](/slides/python-net/pt/aspose.slides.mathtext/mathfractiontypes/) | Tipos de Fração |
| [`MathFunctionsOfOneArgument`](/slides/python-net/pt/aspose.slides.mathtext/mathfunctionsofoneargument/) | Funções matemáticas comuns de um argumento |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/pt/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Funções matemáticas comuns de dois argumentos |
| [`MathHorizontalAlignment`](/slides/python-net/pt/aspose.slides.mathtext/mathhorizontalalignment/) | Alinhamento Horizontal |
| [`MathIntegralTypes`](/slides/python-net/pt/aspose.slides.mathtext/mathintegraltypes/) | Tipos de integral matemática |
| [`MathJustification`](/slides/python-net/pt/aspose.slides.mathtext/mathjustification/) | Especifica a justificação do parágrafo matemático (uma série de instâncias adjacentes de texto matemático dentro do mesmo parágrafo) |
| [`MathLimitLocations`](/slides/python-net/pt/aspose.slides.mathtext/mathlimitlocations/) | Localização dos limites (subscrito/sobrescrito) em operadores n-ários. |
| [`MathNaryOperatorTypes`](/slides/python-net/pt/aspose.slides.mathtext/mathnaryoperatortypes/) | Tipos de operador N-ário IMathNaryOperator (excluindo integrais)<br/>            Para integrais [`MathIntegralTypes`](/slides/python-net/pt/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/pt/aspose.slides.mathtext/mathrowspacingrule/) | O tipo de espaçamento vertical entre colunas em uma matriz ou array |
| [`MathSpacingRules`](/slides/python-net/pt/aspose.slides.mathtext/mathspacingrules/) | Tipos de espaçamento (horizontal) entre colunas de uma matriz |
| [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions/) | Enumeração de posições superior/inferior |
| [`MathVerticalAlignment`](/slides/python-net/pt/aspose.slides.mathtext/mathverticalalignment/) | Alinhamento Vertical |