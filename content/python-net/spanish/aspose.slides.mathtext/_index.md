---
title: aspose.slides.mathtext
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/
---
Contiene clases para trabajar con texto matemático en presentaciones de Microsoft PowerPoint.

## Clases

| Clase | Descripción |
| :- | :- |
| [`BaseScript`](/slides/python-net/es/aspose.slides.mathtext/basescript/) | Script matemático |
| [`IMathAccent`](/slides/python-net/es/aspose.slides.mathtext/imathaccent/) | Especifica la función de acento, que consta de una base y una marca diacrítica combinada<br/>            Example: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/es/aspose.slides.mathtext/imathaccentfactory/) | Permite crear un acento matemático |
| [`IMathArray`](/slides/python-net/es/aspose.slides.mathtext/imatharray/) | Especifica una matriz vertical de ecuaciones o cualquier objeto matemático |
| [`IMathArrayFactory`](/slides/python-net/es/aspose.slides.mathtext/imatharrayfactory/) | Permite crear una matriz matemática |
| [`IMathBar`](/slides/python-net/es/aspose.slides.mathtext/imathbar/) | Especifica la función de barra, que consta de un argumento base y una barra superior o inferior |
| [`IMathBarFactory`](/slides/python-net/es/aspose.slides.mathtext/imathbarfactory/) | Permite crear una barra matemática |
| [`IMathBlock`](/slides/python-net/es/aspose.slides.mathtext/imathblock/) | Especifica una instancia de texto matemático que está contenida dentro de un MathParagraph y comienza en una línea propia.<br/>            Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático. |
| [`IMathBlockCollection`](/slides/python-net/es/aspose.slides.mathtext/imathblockcollection/) | Colección de bloques matemáticos (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/es/aspose.slides.mathtext/imathblockfactory/) | Permite crear un bloque matemático |
| [`IMathBorderBox`](/slides/python-net/es/aspose.slides.mathtext/imathborderbox/) | Dibuja un borde rectangular u otro alrededor del IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/es/aspose.slides.mathtext/imathborderboxfactory/) | Permite crear una caja de borde matemática |
| [`IMathBox`](/slides/python-net/es/aspose.slides.mathtext/imathbox/) | Especifica el empaquetado lógico (boxing) de un elemento matemático.<br/>            Por ejemplo, un objeto en caja puede servir como un emulador de operador con o sin punto de alineación, <br/>            servir como un punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro.<br/>            Por ejemplo, el operador "==" debería estar en caja para prevenir saltos de línea. |
| [`IMathBoxFactory`](/slides/python-net/es/aspose.slides.mathtext/imathboxfactory/) | Permite crear una caja matemática |
| [`IMathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiter/) | Especifica el objeto delimitador, que consta de caracteres de apertura y cierre (como paréntesis, <br/>            llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado.<br/>            Ejemplos: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiterfactory/) | Permite crear un delimitador matemático |
| [`IMathElement`](/slides/python-net/es/aspose.slides.mathtext/imathelement/) | Interfaz base de cualquier elemento matemático: <br/>            fracción, texto matemático, función, expresión con múltiples elementos, etc. |
| [`IMathElementCollection`](/slides/python-net/es/aspose.slides.mathtext/imathelementcollection/) | Representa una colección de elementos matemáticos (MathElement). |
| [`IMathFraction`](/slides/python-net/es/aspose.slides.mathtext/imathfraction/) | Especifica el objeto fracción, que consta de un numerador y un denominador separados por una barra de fracción.<br/>            La barra de fracción puede ser horizontal o diagonal, dependiendo de las propiedades de la fracción.<br/>            El objeto fracción también se utiliza para representar la función de apilamiento, que coloca un elemento encima de otro, sin barra de fracción. |
| [`IMathFractionFactory`](/slides/python-net/es/aspose.slides.mathtext/imathfractionfactory/) | Permite crear una fracción matemática |
| [`IMathFunction`](/slides/python-net/es/aspose.slides.mathtext/imathfunction/) | Especifica una función de un argumento. |
| [`IMathFunctionFactory`](/slides/python-net/es/aspose.slides.mathtext/imathfunctionfactory/) | Permite crear una función matemática |
| [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter/) | Especifica un símbolo de agrupación arriba o abajo de una expresión, usualmente para resaltar la relación entre los elementos |
| [`IMathGroupingCharacterFactory`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Permite crear un carácter de agrupación matemática |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/es/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Especifica el objeto Sub-Superscript, que consta de una base <br/>            y un subíndice y superíndice colocados a la izquierda de la base. |
| [`IMathLimit`](/slides/python-net/es/aspose.slides.mathtext/imathlimit/) | Especifica el objeto Limit, que consta de texto en la línea de base y texto de tamaño reducido inmediatamente arriba o abajo de él. |
| [`IMathLimitFactory`](/slides/python-net/es/aspose.slides.mathtext/imathlimitfactory/) | Permite crear IMathLimit |
| [`IMathMatrix`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/) | Especifica el objeto Matrix, que consta de elementos hijos dispuestos en una o más filas y columnas. <br/>            Es importante notar que las matrices no tienen delimitadores incorporados. <br/>            Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter).<br/>            Los argumentos nulos pueden usarse para crear espacios en las matrices. |
| [`IMathMatrixFactory`](/slides/python-net/es/aspose.slides.mathtext/imathmatrixfactory/) | Permite crear una matriz matemática |
| [`IMathNaryOperator`](/slides/python-net/es/aspose.slides.mathtext/imathnaryoperator/) | Especifica un objeto matemático N-ario, como Summation e Integral.<br/>            Consiste en un operador, una base (u operando) y límites superiores e inferiores opcionales. <br/>            Ejemplos de operadores N-arios son: Summation, Union, Intersection, Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/es/aspose.slides.mathtext/imathnaryoperatorfactory/) | Permite crear IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/es/aspose.slides.mathtext/imathnaryoperatorproperties/) | Especifica propiedades de IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/es/aspose.slides.mathtext/imathparagraph/) | Párrafo matemático que es un contenedor de bloques matemáticos (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/es/aspose.slides.mathtext/imathparagraphfactory/) | Permite crear un párrafo matemático |
| [`IMathPhantom`](/slides/python-net/es/aspose.slides.mathtext/imathphantom/) | Representa un objeto matemático fantasma (<m:phant>) que afecta el diseño de su elemento hijo<br/>            sin necesariamente mostrarse. Un fantasma puede ocultar su expresión base mientras conserva<br/>            su ancho, altura o profundidad para alinear fórmulas o reservar espacio. <br/>            La visibilidad y el comportamiento geométrico se controlan mediante propiedades como Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc y Transp. |
| [`IMathPortion`](/slides/python-net/es/aspose.slides.mathtext/imathportion/) | Representa una porción con contexto matemático interno. |
| [`IMathRadical`](/slides/python-net/es/aspose.slides.mathtext/imathradical/) | Especifica la función radical, que consta de una base y un grado opcional.<br/>            Un ejemplo de objeto radical es √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/es/aspose.slides.mathtext/imathradicalfactory/) | Permite crear un radical matemático |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/es/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Especifica el objeto Sub-Superscript, que consta de una base <br/>            y un subíndice y superíndice colocados a la derecha de la base. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/es/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Permite crear IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/es/aspose.slides.mathtext/imathsubscriptelement/) | Especifica el objeto subíndice, que consta de una base <br/>            y un subíndice de tamaño reducido colocado abajo y a la derecha. |
| [`IMathSubscriptElementFactory`](/slides/python-net/es/aspose.slides.mathtext/imathsubscriptelementfactory/) | Permite crear IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/es/aspose.slides.mathtext/imathsuperscriptelement/) | Especifica el objeto superíndice, que consta de una base <br/>            y un superíndice de tamaño reducido colocado arriba y a la derecha |
| [`IMathSuperscriptElementFactory`](/slides/python-net/es/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Permite crear IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/es/aspose.slides.mathtext/imathematicaltext/) | Texto matemático |
| [`IMathematicalTextFactory`](/slides/python-net/es/aspose.slides.mathtext/imathematicaltextfactory/) | Permite crear un elemento MathematicalText |
| [`MathAccent`](/slides/python-net/es/aspose.slides.mathtext/mathaccent/) | Especifica la función de acento, que consta de una base y una marca diacrítica combinada<br/>            Example: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/es/aspose.slides.mathtext/mathaccentfactory/) | Permite crear un acento matemático |
| [`MathArray`](/slides/python-net/es/aspose.slides.mathtext/matharray/) | Especifica una matriz vertical de ecuaciones o cualquier objeto matemático |
| [`MathArrayFactory`](/slides/python-net/es/aspose.slides.mathtext/matharrayfactory/) | Permite crear una matriz matemática |
| [`MathBar`](/slides/python-net/es/aspose.slides.mathtext/mathbar/) | Especifica la función de barra, que consta de un argumento base y una barra superior o inferior |
| [`MathBarFactory`](/slides/python-net/es/aspose.slides.mathtext/mathbarfactory/) | Permite crear una barra matemática |
| [`MathBlock`](/slides/python-net/es/aspose.slides.mathtext/mathblock/) | Especifica una instancia de texto matemático que está contenida dentro de un MathParagraph y comienza en una línea propia.<br/>            Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático. |
| [`MathBlockFactory`](/slides/python-net/es/aspose.slides.mathtext/mathblockfactory/) | Permite crear un bloque matemático |
| [`MathBorderBox`](/slides/python-net/es/aspose.slides.mathtext/mathborderbox/) | Dibuja un borde rectangular u otro alrededor del IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/es/aspose.slides.mathtext/mathborderboxfactory/) | Permite crear una caja de borde matemática |
| [`MathBox`](/slides/python-net/es/aspose.slides.mathtext/mathbox/) | Especifica el empaquetado lógico (boxing) de un elemento matemático.<br/>            Por ejemplo, un objeto en caja puede servir como un emulador de operador con o sin punto de alineación, <br/>            servir como un punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro.<br/>            Por ejemplo, el operador "==" debería estar en caja para prevenir saltos de línea. |
| [`MathBoxFactory`](/slides/python-net/es/aspose.slides.mathtext/mathboxfactory/) | Permite crear una caja matemática |
| [`MathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/) | Especifica el objeto delimitador, que consta de caracteres de apertura y cierre (como paréntesis, <br/>            llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado.<br/>            Ejemplos: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiterfactory/) | Permite crear un delimitador matemático |
| [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase/) | Clase base para IMathElement con la implementación de algunos métodos que son comunes a todas las clases heredadas<br/>            Solo para uso interno. La clase heredada debe ser IMathElement. |
| [`MathFraction`](/slides/python-net/es/aspose.slides.mathtext/mathfraction/) | Especifica el objeto fracción, que consta de un numerador y un denominador separados por una barra de fracción.<br/>            La barra de fracción puede ser horizontal o diagonal, dependiendo de las propiedades de la fracción.<br/>            El objeto fracción también se utiliza para representar la función de apilamiento, que coloca un elemento encima de otro, sin barra de fracción. |
| [`MathFractionFactory`](/slides/python-net/es/aspose.slides.mathtext/mathfractionfactory/) | Permite crear una fracción matemática |
| [`MathFunction`](/slides/python-net/es/aspose.slides.mathtext/mathfunction/) | Especifica una función de un argumento. |
| [`MathFunctionFactory`](/slides/python-net/es/aspose.slides.mathtext/mathfunctionfactory/) | Permite crear una función matemática |
| [`MathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/) | Especifica un símbolo de agrupación arriba o abajo de una expresión, usualmente para resaltar la relación entre los elementos |
| [`MathGroupingCharacterFactory`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Permite crear un carácter de agrupación matemática |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/es/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Especifica el objeto Sub-Superscript, que consta de una base <br/>            y un subíndice y superíndice colocados a la izquierda de la base. |
| [`MathLimit`](/slides/python-net/es/aspose.slides.mathtext/mathlimit/) | Especifica el objeto Limit, que consta de texto en la línea de base y texto de tamaño reducido inmediatamente arriba o abajo de él. |
| [`MathLimitFactory`](/slides/python-net/es/aspose.slides.mathtext/mathlimitfactory/) | Permite crear IMathLimit |
| [`MathMatrix`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/) | Especifica el objeto Matrix, que consta de elementos hijos dispuestos en una o más filas y columnas. <br/>            Es importante notar que las matrices no tienen delimitadores incorporados. <br/>            Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter).<br/>            Los argumentos nulos pueden usarse para crear espacios en las matrices. |
| [`MathMatrixFactory`](/slides/python-net/es/aspose.slides.mathtext/mathmatrixfactory/) | Permite crear una matriz matemática |
| [`MathNaryOperator`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/) | Especifica un objeto matemático N-ario, como Summation e Integral.<br/>            Consiste en un operador, una base (u operando) y límites superiores e inferiores opcionales. <br/>            Ejemplos de operadores N-arios son: Summation, Union, Intersection, Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperatorfactory/) | Permite crear IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/es/aspose.slides.mathtext/mathparagraph/) | Párrafo matemático que es un contenedor de bloques matemáticos (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/es/aspose.slides.mathtext/mathparagraphfactory/) | Permite crear un párrafo matemático |
| [`MathPhantom`](/slides/python-net/es/aspose.slides.mathtext/mathphantom/) | Representa un objeto matemático fantasma (<m:phant>) que afecta el diseño de su elemento hijo<br/>            sin necesariamente mostrarse. Un fantasma puede ocultar su expresión base mientras conserva<br/>            su ancho, altura o profundidad para alinear fórmulas o reservar espacio. <br/>            La visibilidad y el comportamiento geométrico se controlan mediante propiedades como Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc y Transp. |
| [`MathPortion`](/slides/python-net/es/aspose.slides.mathtext/mathportion/) | Representa una porción con contexto matemático interno. |
| [`MathRadical`](/slides/python-net/es/aspose.slides.mathtext/mathradical/) | Especifica la función radical, que consta de una base y un grado opcional.<br/>            Un ejemplo de objeto radical es √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/es/aspose.slides.mathtext/mathradicalfactory/) | Permite crear un radical matemático |
| [`MathRightSubSuperscriptElement`](/slides/python-net/es/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Especifica el objeto Sub-Superscript, que consta de una base <br/>            y un subíndice y superíndice colocados a la derecha de la base. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/es/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Permite crear IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/es/aspose.slides.mathtext/mathsubscriptelement/) | Especifica el objeto subíndice, que consta de una base <br/>            y un subíndice de tamaño reducido colocado abajo y a la derecha. |
| [`MathSubscriptElementFactory`](/slides/python-net/es/aspose.slides.mathtext/mathsubscriptelementfactory/) | Permite crear IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/es/aspose.slides.mathtext/mathsuperscriptelement/) | Especifica el objeto superíndice, que consta de una base <br/>            y un superíndice de tamaño reducido colocado arriba y a la derecha |
| [`MathSuperscriptElementFactory`](/slides/python-net/es/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Permite crear IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/es/aspose.slides.mathtext/mathematicaltext/) | Texto matemático |
| [`MathematicalTextFactory`](/slides/python-net/es/aspose.slides.mathtext/mathematicaltextfactory/) | Permite crear un elemento MathematicalText |

## Enumeraciones

| Enumeración | Descripción |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/es/aspose.slides.mathtext/mathdelimitershape/) | La ubicación y tamaño de los delimitadores en relación con el contenido de los operandos |
| [`MathFractionTypes`](/slides/python-net/es/aspose.slides.mathtext/mathfractiontypes/) | Tipos de fracción |
| [`MathFunctionsOfOneArgument`](/slides/python-net/es/aspose.slides.mathtext/mathfunctionsofoneargument/) | Funciones matemáticas comunes de un argumento |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/es/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Funciones matemáticas comunes de dos argumentos |
| [`MathHorizontalAlignment`](/slides/python-net/es/aspose.slides.mathtext/mathhorizontalalignment/) | Alineación horizontal |
| [`MathIntegralTypes`](/slides/python-net/es/aspose.slides.mathtext/mathintegraltypes/) | Tipos de integrales matemáticas |
| [`MathJustification`](/slides/python-net/es/aspose.slides.mathtext/mathjustification/) | Especifica la justificación del párrafo matemático (una serie de instancias adyacentes de texto matemático dentro del mismo párrafo) |
| [`MathLimitLocations`](/slides/python-net/es/aspose.slides.mathtext/mathlimitlocations/) | Ubicación de los límites (subíndice/superíndice) en operadores n-arios. |
| [`MathNaryOperatorTypes`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperatortypes/) | Tipos de operadores Nary IMathNaryOperator (excluyendo integrales)<br/>            Para integrales [`MathIntegralTypes`](/slides/python-net/es/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/es/aspose.slides.mathtext/mathrowspacingrule/) | Tipo de espaciado vertical entre columnas en una matriz o arreglo |
| [`MathSpacingRules`](/slides/python-net/es/aspose.slides.mathtext/mathspacingrules/) | Tipos de espacio (espaciado horizontal) entre columnas de una matriz |
| [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions/) | Enumeración de posiciones superior/inferior |
| [`MathVerticalAlignment`](/slides/python-net/es/aspose.slides.mathtext/mathverticalalignment/) | Alineación vertical |