---
title: MathMatrix
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el objeto Matrix que consiste en elementos secundarios dispuestos en una o más filas y columnas. Es importante tener en cuenta que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes, debe utilizar el objeto delimitador IMathDelimiter. Se pueden usar argumentos nulos para crear espacios en las matrices.
type: docs
weight: 8590
url: /es/aspose.slides.mathtext/mathmatrix/
---

## Clase MathMatrix

Especifica el objeto Matrix, que consiste en elementos secundarios dispuestos en una o más filas y columnas. Es importante tener en cuenta que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes, debe utilizar el objeto delimitador (IMathDelimiter). Se pueden usar argumentos nulos para crear espacios en las matrices.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Inicializa una nueva instancia de la clase MathMatrix. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Especifica la justificación vertical con respecto al texto circundante. Los valores posibles son arriba, abajo y centro. Por defecto: Centro |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Número de columnas en la matriz |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | El valor del espaciado horizontal entre columnas de una matriz; Si el ColumnGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si el ColumnGapRule se establece en 4 ("Múltiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Por defecto: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | El tipo de espaciado horizontal entre columnas de una matriz; Las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Por defecto: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Oculta los marcadores de posición para los elementos vacíos de la matriz. Por defecto: falso |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Elemento de la matriz |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Ancho mínimo de columna en twips (1/20 de un punto). El espaciado de los espacios (también conocido como “Column Gap” o “Gap Width”) se añade a MinColumnWidth para determinar el espaciado total de la columna de la matriz (distancia entre los mismos bordes de diferentes columnas). Por defecto: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Número de filas en la matriz |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | El valor del espaciado vertical entre filas de una matriz; Si el RowGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si el RowGapRule se establece en 4 ("Múltiple"), entonces la unidad se interpreta como medios renglones. Por defecto: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | El tipo de espaciado vertical entre filas de una matriz; Las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Por defecto: SingleSpacingGap (0) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece un signo de acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Toma una función específica utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Toma una función específica utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Toma una función específica utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Toma una función específica utilizando esta instancia como argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Toma una función específica utilizando esta instancia como argumento y el argumento adicional especificado |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Elimina la columna especificada |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Elimina la fila especificada |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encierra un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encierra un elemento matemático en los caracteres especificados, como paréntesis u otros caracteres como enmarcadores |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento utilizando esta instancia como el nombre de la función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento utilizando esta instancia como el nombre de la función |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Obtiene los elementos hijos |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Obtiene la alineación horizontal de la columna especificada |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo utilizando un corchete de cierre |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo utilizando un carácter de agrupamiento como un corchete de cierre u otro |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Inserta una nueva columna después de la especificada. Inicialmente, todos los elementos en la nueva columna son nulos. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Inserta una nueva columna antes de la especificada. Inicialmente, todos los elementos en la nueva columna son nulos. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Inserta una nueva fila después de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Inserta una nueva fila antes de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Toma la integral sin límites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Toma la integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Une un elemento matemático y forma un bloque matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Une un texto matemático y forma un bloque matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operador N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operador N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Establece una barra en la parte superior de este elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática del grado dado del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática del grado dado del argumento especificado. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Establece la alineación horizontal de la columna especificada |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Establece la alineación horizontal de las columnas especificadas |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Toma el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Toma el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea un subíndice y un superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea un superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea un superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Toma el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Toma el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea, o estar agrupado de tal manera que no permita saltos de línea en su interior. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca en un arreglo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Véase También

* clase [MathElementBase](../mathelementbase)
* interfaz [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->