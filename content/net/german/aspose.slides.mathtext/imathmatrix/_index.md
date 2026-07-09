---
title: IMathMatrix
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt das Matrix-Objekt an, das aus Kind-Elementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen besitzen. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichen-Objekt IMathDelimiter verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen.
type: docs
weight: 8340
url: /de/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix Schnittstelle

Gibt das Matrix-Objekt an, das aus Kind-Elementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen besitzen. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt (IMathDelimiter) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen.

```csharp
public interface IMathMatrix : IMathElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Ermöglicht das Abrufen der Basis-IMathElement-Schnittstelle [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. Mögliche Werte sind top, bottom und center. Standard: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Anzahl der Spalten in der Matrix |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Der Wert des horizontalen Abstands zwischen den Spalten einer Matrix; Wenn die ColumnGapRule auf 3 ("Exactly") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 ("Multiple") gesetzt ist, wird die Einheit als Anzahl von 0.5-em-Schritten interpretiert. In anderen Fällen wird sie ignoriert. Standard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Versteckt die Platzhalter für leere Matrix-Elemente. Standard: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elemente der Matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Mindestspaltenbreite in Twips (1/20 eines Punktes). Der Abstand (auch bezeichnet als „Column Gap“ oder „Gap Width“) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand (Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Standard: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Anzahl der Zeilen in der Matrix |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Der Wert des vertikalen Abstands zwischen den Zeilen einer Matrix; Wenn die RowGapRule auf 3 ("Exactly") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die RowGapRule auf 4 ("Multiple") gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Löscht die angegebene Spalte |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Löscht die angegebene Zeile |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Gibt die horizontale Ausrichtung der angegebenen Spalte zurück |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Fügt eine neue Spalte nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Fügt eine neue Spalte vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Fügt eine neue Zeile nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Fügt eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Setzt die horizontale Ausrichtung der angegebenen Spalte |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Setzt die horizontale Ausrichtung der angegebenen Spalten |

### Beispiele

Beispiel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Siehe auch

* Schnittstelle [IMathElement](../imathelement)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->