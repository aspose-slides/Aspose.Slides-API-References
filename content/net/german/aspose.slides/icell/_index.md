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
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Bestimmt, ob das Textfeld in einer Zelle zentriert ist oder nicht. Lese-/Schreibzugriff Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Ermöglicht den Zugriff auf die Grundschnittstelle ISlideComponent. Nur Lesezugriff [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungsattribute für diese Zelle enthält. Nur Lesezugriff [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Gibt die Anzahl der Rasterspalten im Raster der übergeordneten Tabelle zurück, die von der aktuellen Zelle überspannt werden sollen. Diese Eigenschaft ermöglicht es Zellen, den Anschein zu erwecken, dass sie zusammengeführt sind, da sie die vertikalen Grenzen anderer Zellen in der Tabelle überschreiten. Nur Lesezugriff Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Gibt die erste Spalte der Zelle zurück. Nur Lesezugriff [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Gibt den Index der ersten Spalte zurück, die von der Zelle überdeckt wird. Nur Lesezugriff Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Gibt die erste Zeile der Zelle zurück. Nur Lesezugriff [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Gibt den Index der ersten Zeile zurück, die von der Zelle überdeckt wird. Nur Lesezugriff Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Gibt die Höhe der Zelle zurück. Nur Lesezugriff Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false. Nur Lesezugriff Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle überdeckten Zeilen. Nur Lesezugriff Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Gibt die Entfernung von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur Lesezugriff Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Gibt die Entfernung von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur Lesezugriff Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle umfasst. Dies wird in Kombination mit dem vMerge-Attribut auf anderen Zellen verwendet, um die Anfangszelle einer horizontalen Zusammenführung zu bestimmen. Nur Lesezugriff Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Gibt das übergeordnete Tabellenobjekt für eine Zelle zurück. Nur Lesezugriff [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Gibt den Textanker-Typ zurück oder setzt ihn. Lese-/Schreibzugriff [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Gibt den Textrahmen einer Zelle zurück. Nur Lesezugriff [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Gibt den Typ von vertikalem Text zurück oder setzt ihn. Lese-/Schreibzugriff [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Gibt die Breite der Zelle zurück. Nur Lesezugriff Double. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Teilt die Zelle anhand des Spaltenindex in zwei Zellen. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Teilt die Zelle anhand des Zeilenindex in zwei Zellen. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* Schnittstelle [ISlideComponent](../islidecomponent)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->