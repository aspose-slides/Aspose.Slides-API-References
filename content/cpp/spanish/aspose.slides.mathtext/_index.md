---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides para la referencia de la API de C++
description: 
type: docs
weight: 157
url: /es/aspose.slides.mathtext/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [BaseScript](./basescript/) | Script matemático |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) con [Control](../aspose.slides/control/) Propiedades de carácter |
| [IMathAccent](./imathaccent/) | Especifica la función de acento, que consta de una base y una marca diacrítica combinada. Ejemplo: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Permite crear un acento matemático |
| [IMathArray](./imatharray/) | Especifica una matriz vertical de ecuaciones o cualquier objeto matemático |
| [IMathArrayFactory](./imatharrayfactory/) | Permite crear una matriz matemática |
| [IMathBar](./imathbar/) | Especifica la función de barra, que consta de un argumento base y una barra superior o inferior |
| [IMathBarFactory](./imathbarfactory/) | Permite crear una barra matemática |
| [IMathBlock](./imathblock/) | Especifica una instancia de texto matemático que se encuentra dentro de un [MathParagraph](./mathparagraph/) y comienza en una línea propia. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático. |
| [IMathBlockCollection](./imathblockcollection/) | Colección de bloques matemáticos ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Permite crear un bloque matemático |
| [IMathBorderBox](./imathborderbox/) | Dibuja un borde rectangular u otro alrededor del [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Permite crear una caja de borde matemático |
| [IMathBox](./imathbox/) | Especifica el encajado lógico (empaquetado) de un elemento matemático. Por ejemplo, un objeto en caja puede servir como emulador de operador con o sin un punto de alineación, servir como punto de salto de línea, o agruparse de manera que no permita saltos de línea internos. Por ejemplo, el operador \"==\" debería estar en caja para evitar saltos de línea. |
| [IMathBoxFactory](./imathboxfactory/) | Permite crear una caja matemática |
| [IMathDelimiter](./imathdelimiter/) | Especifica el objeto delimitador, que consta de caracteres de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Permite crear un delimitador matemático |
| [IMathElement](./imathelement/) | Interfaz base de cualquier elemento matemático: fracción, texto matemático, función, expresión con múltiples elementos, etc. |
| [IMathElementCollection](./imathelementcollection/) | Representa una colección de elementos matemáticos (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Texto matemático |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Permite crear un elemento [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Especifica el objeto fracción, que consta de un numerador y un denominador separados por una barra de fracción. La barra de fracción puede ser horizontal o diagonal, según las propiedades de la fracción. El objeto fracción también se usa para representar la función de apilamiento, que coloca un elemento sobre otro, sin barra de fracción. |
| [IMathFractionFactory](./imathfractionfactory/) | Permite crear una fracción matemática |
| [IMathFunction](./imathfunction/) | Especifica una función de un argumento. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Permite crear una función matemática |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Especifica un símbolo de agrupación arriba o abajo de una expresión, usualmente para resaltar la relación entre elementos |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Permite crear un carácter de agrupación matemático |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Especifica el objeto Subíndice-Superíndice, que consta de una base y un subíndice y superíndice colocados a la izquierda de la base. |
| [IMathLimit](./imathlimit/) | Especifica el objeto Límite, que consta de texto en la línea base y texto de tamaño reducido inmediatamente arriba o abajo de él. |
| [IMathLimitFactory](./imathlimitfactory/) | Permite crear [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Especifica el objeto Matriz, que consta de elementos hijo distribuidos en una o más filas y columnas. Es importante notar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes debe usar el objeto delimitador ([IMathDelimiter](./imathdelimiter/)). Los argumentos nulos pueden emplearse para crear espacios en las matrices. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Permite crear una matriz matemática |
| [IMathNaryOperator](./imathnaryoperator/) | Especifica un objeto matemático N-ario, como Suma e Integral. Consiste en un operador, una base (u operando) y límites superiores e inferiores opcionales. Ejemplos de operadores N-arios son: Suma, Unión, Intersección, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Permite crear [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Especifica propiedades de [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Párrafo matemático que es un contenedor de bloques matemáticos ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Permite crear un párrafo matemático |
| [IMathPhantom](./imathphantom/) | Representa un objeto matemático fantasma (<m:phant>) que afecta el diseño de su elemento hijo sin necesariamente mostrarse. Un fantasma puede ocultar su expresión base mientras preserva su ancho, altura o profundidad para alinear fórmulas o reservar espacio. La visibilidad y el comportamiento geométrico se controlan mediante propiedades como Show, ZeroWid, ZeroAsc, ZeroDesc y Transp. |
| [IMathPortion](./imathportion/) | Representa una porción con contexto matemático dentro. |
| [IMathRadical](./imathradical/) | Especifica la función radical, que consta de una base y un grado opcional. Un ejemplo de objeto radical es \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Permite crear un radical matemático |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Especifica el objeto Subíndice-Superíndice, que consta de una base y un subíndice y superíndice colocados a la derecha de la base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Permite crear [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Especifica el objeto subíndice, que consta de una base y un subíndice de tamaño reducido colocado abajo y a la derecha. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Permite crear [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Especifica el objeto superíndice, que consta de una base y un superíndice de tamaño reducido colocado arriba y a la derecha |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Permite crear [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Especifica la función de acento, que consta de una base y una marca diacrítica combinada. Ejemplo: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Permite crear un acento matemático |
| [MathArray](./matharray/) | Especifica una matriz vertical de ecuaciones o cualquier objeto matemático |
| [MathArrayFactory](./matharrayfactory/) | Permite crear una matriz matemática |
| [MathBar](./mathbar/) | Especifica la función de barra, que consta de un argumento base y una barra superior o inferior |
| [MathBarFactory](./mathbarfactory/) | Permite crear una barra matemática |
| [MathBlock](./mathblock/) | Especifica una instancia de texto matemático que se encuentra dentro de un [MathParagraph](./mathparagraph/) y comienza en una línea propia. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático. |
| [MathBlockFactory](./mathblockfactory/) | Permite crear un bloque matemático |
| [MathBorderBox](./mathborderbox/) | Dibuja un borde rectangular u otro alrededor del [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Permite crear una caja de borde matemático |
| [MathBox](./mathbox/) | Especifica el encajado lógico (empaquetado) de un elemento matemático. Por ejemplo, un objeto en caja puede servir como emulador de operador con o sin un punto de alineación, servir como punto de salto de línea, o agruparse de manera que no permita saltos de línea internos. Por ejemplo, el operador \"==\" debería estar en caja para evitar saltos de línea. |
| [MathBoxFactory](./mathboxfactory/) | Permite crear una caja matemática |
| [MathDelimiter](./mathdelimiter/) | Especifica el objeto delimitador, que consta de caracteres de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Permite crear un delimitador matemático |
| [MathElementBase](./mathelementbase/) | Clase base para [IMathElement](./imathelement/) con la implementación de algunos métodos comunes a todas las clases heredadas. Solo uso interno. La clase heredada debe ser [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Texto matemático |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Permite crear un elemento [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Especifica el objeto fracción, que consta de un numerador y un denominador separados por una barra de fracción. La barra de fracción puede ser horizontal o diagonal, según las propiedades de la fracción. El objeto fracción también se usa para representar la función de apilamiento, que coloca un elemento sobre otro, sin barra de fracción. |
| [MathFractionFactory](./mathfractionfactory/) | Permite crear una fracción matemática |
| [MathFunction](./mathfunction/) | Especifica una función de un argumento. |
| [MathFunctionFactory](./mathfunctionfactory/) | Permite crear una función matemática |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Especifica un símbolo de agrupación arriba o abajo de una expresión, usualmente para resaltar la relación entre elementos |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Permite crear un carácter de agrupación matemática |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Especifica el objeto Subíndice-Superíndice, que consta de una base y un subíndice y superíndice colocados a la izquierda de la base. |
| [MathLimit](./mathlimit/) | Especifica el objeto Límite, que consta de texto en la línea base y texto de tamaño reducido inmediatamente arriba o abajo de él. |
| [MathLimitFactory](./mathlimitfactory/) | Permite crear [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Especifica el objeto Matriz, que consta de elementos hijo distribuidos en una o más filas y columnas. Es importante notar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes debe usar el objeto delimitador ([IMathDelimiter](./imathdelimiter/)). Los argumentos nulos pueden emplearse para crear espacios en las matrices. |
| [MathMatrixFactory](./mathmatrixfactory/) | Permite crear una matriz matemática |
| [MathNaryOperator](./mathnaryoperator/) | Especifica un objeto matemático N-ario, como Suma e Integral. Consiste en un operador, una base (u operando) y límites superiores e inferiores opcionales. Ejemplos de operadores N-arios son: Suma, Unión, Intersección, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Permite crear [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Párrafo matemático que es un contenedor de bloques matemáticos ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Permite crear un párrafo matemático |
| [MathPhantom](./mathphantom/) | Representa un objeto matemático fantasma (<m:phant>) que afecta el diseño de su elemento hijo sin necesariamente mostrarse. Un fantasma puede ocultar su expresión base mientras preserva su ancho, altura o profundidad para alinear fórmulas o reservar espacio. La visibilidad y el comportamiento geométrico se controlan mediante propiedades como Show, ZeroWid, ZeroAsc, ZeroDesc y Transp. |
| [MathPortion](./mathportion/) | Representa una porción con contexto matemático dentro. |
| [MathRadical](./mathradical/) | Especifica la función radical, que consta de una base y un grado opcional. Un ejemplo de objeto radical es \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Permite crear un radical matemático |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Especifica el objeto Subíndice-Superíndice, que consta de una base y un subíndice y superíndice colocados a la derecha de la base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Permite crear [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Especifica el objeto subíndice, que consta de una base y un subíndice de tamaño reducido colocado abajo y a la derecha. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Permite crear [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Especifica el objeto superíndice, que consta de una base y un superíndice de tamaño reducido colocado arriba y a la derecha |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Permite crear [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | La ubicación y el tamaño de los delimitadores respecto al contenido de los operandos |
| [MathFractionTypes](./mathfractiontypes/) | Tipos de fracción |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Funciones matemáticas comunes de un argumento |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Funciones matemáticas comunes de dos argumentos |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Alineación horizontal |
| [MathIntegralTypes](./mathintegraltypes/) | Tipos de integrales matemáticas |
| [MathJustification](./mathjustification/) | Especifica la justificación del párrafo matemático (una serie de instancias adyacentes de texto matemático dentro del mismo párrafo) |
| [MathLimitLocations](./mathlimitlocations/) | Ubicación de los límites (subíndice/superíndice) en operadores n-arios. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Tipos de operador n-ario [IMathNaryOperator](./imathnaryoperator/) (excluyendo integrales). Para integrales [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | El tipo de espaciado vertical entre columnas en una matriz o arreglo |
| [MathSpacingRules](./mathspacingrules/) | Tipos de brecha (espaciado horizontal) entre columnas de una matriz |
| [MathTopBotPositions](./mathtopbotpositions/) | Enumeración de posiciones superior/inferior |
| [MathVerticalAlignment](./mathverticalalignment/) | Alineación vertical |