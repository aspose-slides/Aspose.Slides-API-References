---
title: ICell
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Zelle in einer Tabelle dar.
type: docs
weight: 5450
url: /de/aspose.slides/icell/
---
## ICell Schnittstelle

Stellt eine Zelle in einer Tabelle dar.

```csharp
public interface ICell : ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Bestimmt, ob das Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lese-/Schreib Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Ermöglicht das Abrufen der Basis-ISlideComponent-Schnittstelle. Nur-Lesen [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Nur-Lesen [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Gibt die Anzahl der Gitterspalten im Tabellenraster der übergeordneten Tabelle zurück, die von der aktuellen Zelle überlappt werden sollen. Diese Eigenschaft ermöglicht es Zellen, den Anschein einer Zusammenführung zu haben, indem sie vertikale Grenzen anderer Zellen in der Tabelle überspannen. Nur-Lesen Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Ermittelt die erste Spalte der Zelle. Nur-Lesen [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Gibt den Index der ersten von der Zelle bedeckten Spalte zurück. Nur-Lesen Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Ermittelt die erste Zeile der Zelle. Nur-Lesen [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Gibt den Index der ersten von der Zelle bedeckten Zeile zurück. Nur-Lesen Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Gibt die Höhe der Zelle zurück. Nur-Lesen Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false. Nur-Lesen Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Gibt die Mindesthöhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle bedeckten Zeilen. Nur-Lesen Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Gibt den Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur-Lesen Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Gibt den Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur-Lesen Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut anderer Zellen verwendet, um die Ausgangszelle einer horizontalen Zusammenführung zu spezifizieren. Nur-Lesen Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Gibt das übergeordnete Table-Objekt einer Zelle zurück. Nur-Lesen [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Gibt den Text-Ankertyp zurück oder setzt ihn. Lese-/Schreib [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Gibt den TextFrame einer Zelle zurück. Nur-Lesen [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Gibt den Typ vertikalen Textes zurück oder legt ihn fest. Lese-/Schreib [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Gibt die Breite der Zelle zurück. Nur-Lesen Double. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Teilt die Zelle anhand des Spaltenindexes in zwei Zellen. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Teilt die Zelle anhand des Zeilenindexes in zwei Zellen. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* Schnittstelle [ISlideComponent](../islidecomponent)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->