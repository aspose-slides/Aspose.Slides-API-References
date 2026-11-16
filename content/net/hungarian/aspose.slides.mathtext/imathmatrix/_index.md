---
title: IMathMatrix
second_title: Aspose.Sildes a .NET-hez API referencia
description: Megadja a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorba és oszlopba van elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrix szögletes zárójelek közé helyezéséhez a határoló objektumot, az IMathDelimiter-t kell használni. Null argumentumokkal lehet réseket létrehozni a mátrixokban.
type: docs
weight: 8360
url: /hu/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interfész

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Lehetővé teszi az alap IMathElement interfész [`IMathElement`](../imathelement) lekérését |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | A mátrix oszlopainak száma |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | A vízszintes távolság értéke a mátrix oszlopai között; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | A vízszintes távolság típusát a mátrix oszlopai között; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Elrejti az üres mátrix elemek helyőrzőit. Default: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | A mátrix elemei |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | A mátrix sorainak száma |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |

## Metódusok

| Név | Leírás |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Törli a megadott oszlopot |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Törli a megadott sort |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Lekéri a megadott oszlop vízszintes igazítását |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Új oszlop beszúrása a megadott után. Initially all elements in the new column are null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Új oszlop beszúrása a megadott előtt. Initially all elements in the new column are null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Új sor beszúrása a megadott után. Initially all elements in the new row are null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Új sor beszúrása a megadott előtt. Initially all elements in the new row are null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Beállítja a megadott oszlop vízszintes igazítását |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Beállítja a megadott oszlopok vízszintes igazítását |

### Példák

Példa:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Lásd még

* interfész [IMathElement](../imathelement)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->