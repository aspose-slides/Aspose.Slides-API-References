---
title: IMathMatrix
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica el objeto Matrix que consta de elementos secundarios dispuestos en una o más filas y columnas. Es importante tener en cuenta que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre paréntesis debe usar el objeto delimitador IMathDelimiter. Se pueden usar argumentos nulos para crear espacios en las matrices.
type: docs
weight: 7630
url: /es/net/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Especifica el objeto Matrix, que consta de elementos secundarios dispuestos en una o más filas y columnas. Es importante tener en cuenta que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre paréntesis, debe usar el objeto delimitador (IMathDelimiter). Se pueden usar argumentos nulos para crear espacios en las matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Especifica la justificación vertical respecto al texto circundante. Los valores posibles son superior, inferior y central. Valor predeterminado: Centro |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Número de columnas en la matriz |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | El valor del espaciado horizontal entre las columnas de una matriz; Si ColumnGapRule se establece en 3 ("Exactamente"), la unidad se interpreta como twips (1/20 de un punto) Si ColumnGapRule se establece en 4 ( "Múltiple"), la unidad se interpreta como un número de incrementos de 0,5 em. En otros casos, se ignora. Valor predeterminado: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | El tipo de espaciado horizontal entre columnas de una matriz; Las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Ocultar los marcadores de posición para elementos de matriz vacíos Predeterminado: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementos de matriz |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Ancho mínimo de columna en twips (1/20 de un punto) El espaciado de espacio (también conocido como "Espacio de columna" o "Ancho de espacio") se agrega a MinColumnWidth para determinar el Espaciado de columna de matriz total (distancia entre el mismos bordes de diferentes columnas). Predeterminado: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Número de filas en la matriz |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | El valor del espaciado vertical entre filas de una matriz; Si RowGapRule se establece en 3 ("Exactamente"), la unidad se interpreta como twips (1/20 de un punto) Si RowGapRule se establece en 4 ( "Múltiple"), la unidad se interpreta como medias líneas. Valor predeterminado: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | El tipo de espaciado vertical entre filas de una matriz; Las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Elimina la columna especificada |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Elimina la fila especificada |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Obtener la alineación horizontal de la columna especificada |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Inserta una nueva columna después de la especificada Inicialmente todos los elementos en la nueva columna son nulos. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Inserta una nueva columna antes de la especificada Inicialmente todos los elementos en la nueva columna son nulos. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Inserta una nueva fila después de la especificada Inicialmente, todos los elementos en la nueva fila son nulos. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Insertar una nueva fila antes de la especificada Inicialmente todos los elementos en la nueva fila son nulos. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Establecer la alineación horizontal de la columna especificada |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Establecer la alineación horizontal de las columnas especificadas |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Ver también

* interface [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
