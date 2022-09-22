---
title: IMathMatrix
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt das MatrixObjekt an das aus untergeordneten Elementen besteht die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten dass Matrizen keine eingebauten Trennzeichen haben. Um die Matrix in Klammern zu platzieren sollten Sie das Trennzeichenobjekt IMathDelimiter verwenden. NullArgumente können verwendet werden um Lücken in Matrizen zu erstellen.
type: docs
weight: 7660
url: /de/net/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Gibt das Matrix-Objekt an, das aus untergeordneten Elementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen haben. Um die Matrix in Klammern zu platzieren, sollten Sie das Trennzeichenobjekt (IMathDelimiter) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erstellen.

```csharp
public interface IMathMatrix : IMathElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Ermöglicht das Abrufen von Basis-IMathElement interface [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Gibt die vertikale Ausrichtung in Bezug auf den umgebenden Text an. Mögliche Werte sind top, bottom und center. Standard: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Anzahl der Spalten in der Matrix |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Der Wert des horizontalen Abstands zwischen den Spalten einer Matrix; Wenn die ColumnGapRule auf 3 ("Genau") gesetzt ist, dann wird die Einheit als Twips (1/20 eines Punktes) interpretiert Wenn die ColumnGapRule auf 4 gesetzt ist ( "Multiple"), dann wird die Einheit als Zahl von 0,5 em-Schritten interpretiert. Sonst ignoriert. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; Horizontale Abstandseinheiten können Ems oder Punkte sein (gespeichert als Twips). Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Platzhalter für leere Matrixelemente ausblenden Default: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elemente der Matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimale Spaltenbreite in Twips (1/20stel eines Punktes) Der Lückenabstand (auch als „Spaltenlücke“ oder „Lückenbreite“ bezeichnet) wird zu der MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand (Abstand zwischen den gleiche Kanten verschiedener Spalten). Default: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Anzahl der Zeilen in der Matrix |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn die RowGapRule auf 3 ("Genau") gesetzt ist, dann wird die Einheit als Twips (1/20 eines Punktes) interpretiert Wenn die RowGapRule auf 4 gesetzt ist ( "Multiple"), dann wird die Einheit als Halbzeilen interpretiert. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; Vertikale Abstandseinheiten können Linien oder Punkte sein (gespeichert als Twips). Standard: SingleSpacingGap (0) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Löscht die angegebene Spalte |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Löscht die angegebene Zeile |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Holt die horizontale Ausrichtung der angegebenen Spalte |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Fügt eine neue Spalte nach der angegebenen Eins ein Anfangs sind alle Elemente in der neuen Spalte null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Fügt eine neue Spalte vor der angegebenen ein Anfangs sind alle Elemente in der neuen Spalte null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Fügt eine neue Zeile nach der angegebenen Zeile ein Anfangs sind alle Elemente in der neuen Zeile null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Fügt eine neue Zeile vor der angegebenen Zeile ein Anfangs sind alle Elemente in der neuen Zeile null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Legen Sie die horizontale Ausrichtung der angegebenen Spalte fest |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Legen Sie die horizontale Ausrichtung der angegebenen Spalten fest |

### Beispiele

Beispiel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Siehe auch

* interface [IMathElement](../imathelement)
* namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
