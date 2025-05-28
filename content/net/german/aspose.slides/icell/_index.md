---
title: ICell
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Zelle in einer Tabelle dar.
type: docs
weight: 5250
url: /de/aspose.slides/icell/
---

## ICell-Schnittstelle

Stellt eine Zelle in einer Tabelle dar.

```csharp
public interface ICell : ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Bestimmt, ob das Textfeld zentriert innerhalb einer Zelle ist. Lese-/Schreib-Boolescher Wert. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Ermöglicht den Zugriff auf die Basis-ISlideComponent-Schnittstelle. Nur lesbar [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Nur lesbar [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Gibt die Anzahl der Gitterspalten im Tabellenraster der übergeordneten Tabelle zurück, die von der aktuellen Zelle überspannt werden sollen. Diese Eigenschaft ermöglicht es Zellen, den Anschein von Zusammenführung zu haben, da sie die vertikalen Grenzen anderer Zellen in der Tabelle überschreiten. Nur lesbar Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Gibt die erste Spalte der Zelle zurück. Nur lesbar [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Gibt den Index der ersten Spalte zurück, die von der Zelle abgedeckt wird. Nur lesbar Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Gibt die erste Zeile der Zelle zurück. Nur lesbar [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Gibt den Index der ersten Zeile zurück, die von der Zelle abgedeckt wird. Nur lesbar Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Gibt die Höhe der Zelle zurück. Nur lesbar Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false. Nur lesbar Boolescher Wert. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreib-Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle abgedeckten Zeilen. Nur lesbar Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Gibt den Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur lesbar Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Gibt den Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur lesbar Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut auf anderen Zellen verwendet, um die Anfangszelle einer horizontalen Zusammenführung anzugeben. Nur lesbar Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Gibt das übergeordnete Tabellenobjekt für eine Zelle zurück. Nur lesbar [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Gibt den Textanker-Typ zurück oder setzt ihn. Lese-/Schreib [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Gibt den Textrahmen einer Zelle zurück. Nur lesbar [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Gibt den Typ des vertikalen Texts zurück oder setzt ihn. Lese-/Schreib [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Gibt die Breite der Zelle zurück. Nur lesbar Double. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Teilt die Zelle in zwei Zellen nach dem Index der Spalte. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Teilt die Zelle in zwei Zellen nach dem Index der Zeile. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* Schnittstelle [ISlideComponent](../islidecomponent)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->