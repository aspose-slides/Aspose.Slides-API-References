---
title: Cell
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt eine Zelle einer Tabelle dar.
type: docs
weight: 1130
url: /de/aspose.slides/cell/
---
## Cell Klasse

Stellt eine Zelle einer Tabelle dar.

```csharp
public class Cell : ICell
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lesen/Schreiben Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Nur-Lesen [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Gibt die Anzahl der Rasterspalten im Tabellengitter der übergeordneten Tabelle zurück, die von der aktuellen Zelle überdeckt werden sollen. Diese Eigenschaft ermöglicht es Zellen, den Anschein einer Zusammenführung zu haben, da sie vertikale Grenzen anderer Zellen in der Tabelle überbrücken. Nur-Lesen Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Ermittelt die erste Spalte der Zelle. Nur-Lesen [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Gibt den Index der ersten von der Zelle bedeckten Spalte zurück. Nur-Lesen Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Ermittelt die erste Zeile der Zelle. Nur-Lesen [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Gibt den Index der ersten von der Zelle bedeckten Zeile zurück. Nur-Lesen Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Gibt die Höhe der Zelle zurück. Nur-Lesen Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false. Nur-Lesen Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle bedeckten Zeilen. Nur-Lesen Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Gibt den Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur-Lesen Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Gibt den Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur-Lesen Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Gibt die übergeordnete Präsentation einer Zelle zurück. Nur-Lesen [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut anderer Zellen verwendet, um die Anfangszelle einer horizontalen Zusammenführung anzugeben. Nur-Lesen Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Gibt die übergeordnete Folie einer Zelle zurück. Nur-Lesen [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Gibt das übergeordnete Table-Objekt einer Zelle zurück. Nur-Lesen [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Gibt den Textanker-Typ zurück oder setzt ihn. Lesen/Schreiben [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Gibt das TextFrame einer Zelle zurück. Nur-Lesen [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Gibt den Typ von vertikalem Text zurück oder setzt ihn. Lesen/Schreiben [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Gibt die Breite der Zelle zurück. Nur-Lesen Double. |

## Methoden

| Name | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Teilt die Zelle anhand des Spaltenindex in zwei Zellen. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Teilt die Zelle anhand des Zeilenindex in zwei Zellen. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* Schnittstelle [ICell](../icell)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->