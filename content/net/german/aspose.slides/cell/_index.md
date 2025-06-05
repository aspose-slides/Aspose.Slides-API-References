---
title: Cell
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Zelle einer Tabelle dar.
type: docs
weight: 1050
url: /de/aspose.slides/cell/
---

## Cell-Klasse

Stellt eine Zelle einer Tabelle dar.

```csharp
public class Cell : ICell
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Bestimmt, ob das Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lese-/Schreib-Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungsattribute für diese Zelle enthält. Nur lesbar [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Gibt die Anzahl der Rasterspalten im Tabellenraster der übergeordneten Tabelle zurück, die von der aktuellen Zelle überspannt werden sollen. Diese Eigenschaft ermöglicht es Zellen, das Aussehen zu haben, als wären sie zusammengeführt, da sie vertikale Grenzen anderer Zellen in der Tabelle überschreiten. Nur lesbar Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Gibt die erste Spalte der Zelle zurück. Nur lesbar [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Gibt einen Index der ersten Spalte zurück, die von der Zelle abgedeckt wird. Nur lesbar Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Gibt die erste Reihe der Zelle zurück. Nur lesbar [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Gibt einen Index der ersten Reihe zurück, die von der Zelle abgedeckt wird. Nur lesbar Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Gibt die Höhe der Zelle zurück. Nur lesbar Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false. Nur lesbar Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Gibt die minimale Höhe einer Zelle zurück. Dies ist eine Summe der minimalen Höhen aller von der Zelle abgedeckten Reihen. Nur lesbar Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Gibt eine Entfernung von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur lesbar Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Gibt eine Entfernung von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur lesbar Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Gibt die übergeordnete Präsentation einer Zelle zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Gibt die Anzahl der Reihen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut auf anderen Zellen verwendet, um die Anfangszelle eines horizontalen Mergers anzugeben. Nur lesbar Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Gibt die übergeordnete Folie einer Zelle zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Gibt das übergeordnete Table-Objekt für eine Zelle zurück. Nur lesbar [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Gibt den Textanker-Typ zurück oder setzt ihn. Lese-/Schreib [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Gibt das Textfeld einer Zelle zurück. Nur lesbar [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Gibt den Typ des vertikalen Textes zurück oder setzt ihn. Lese-/Schreib [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Gibt die Breite der Zelle zurück. Nur lesbar Double. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Teilt die Zelle in zwei Zellen nach dem Index der Spalte. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Teilt die Zelle in zwei Zellen nach dem Index der Reihe. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* Schnittstelle [ICell](../icell)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->