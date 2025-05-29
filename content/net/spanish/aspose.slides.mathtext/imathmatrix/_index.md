---
title: IMathMatrix
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el objeto Matrix que consiste en elementos secundarios dispuestos en una o más filas y columnas. Es importante destacar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes, debe utilizar el objeto delimitador IMathDelimiter. Los argumentos nulos se pueden usar para crear espacios en las matrices.
type: docs
weight: 8090
url: /es/aspose.slides.mathtext/imathmatrix/
---

## Interfaz IMathMatrix

Especifica el objeto Matrix, que consiste en elementos secundarios dispuestos en una o más filas y columnas. Es importante destacar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes, debe utilizar el objeto delimitador (IMathDelimiter). Los argumentos nulos se pueden usar para crear espacios en las matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Especifica la justificación vertical respecto al texto circundante. Los valores posibles son arriba, abajo y centro. Predeterminado: Centro |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Número de columnas en la matriz |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | El valor del espaciado horizontal entre columnas de una matriz; Si ColumnGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si ColumnGapRule se establece en 4 ("Múltiplo"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | El tipo de espaciado horizontal entre columnas de una matriz; Las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Oculta los marcadores de posición para los elementos de matriz vacíos. Predeterminado: falso |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementos de la matriz |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Ancho mínimo de columna en twips (1/20 de un punto). El espaciado de la brecha (también denominado "Espacio de columna" o "Ancho de brecha") se agrega a MinColumnWidth para determinar el Espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Número de filas en la matriz |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | El valor del espaciado vertical entre filas de una matriz; Si RowGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si RowGapRule se establece en 4 ("Múltiplo"), entonces la unidad se interpreta como media línea. Predeterminado: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | El tipo de espaciado vertical entre filas de una matriz; Las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Elimina la columna especificada |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Elimina la fila especificada |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Obtiene la alineación horizontal de la columna especificada |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Inserta una nueva columna después de la especificada. Inicialmente, todos los elementos en la nueva columna son nulos. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Inserta una nueva columna antes de la especificada. Inicialmente, todos los elementos en la nueva columna son nulos. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Inserta una nueva fila después de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Inserta una nueva fila antes de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Establece la alineación horizontal de la columna especificada |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Establece la alineación horizontal de las columnas especificadas |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Ver También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->