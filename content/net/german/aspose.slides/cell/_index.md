---
title: Cell
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert eine Zelle einer Tabelle.
type: docs
weight: 1010
url: /de/aspose.slides/cell/
---
## Cell class

Repräsentiert eine Zelle einer Tabelle.

```csharp
public class Cell : ICell
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lesen/SchreibenBoolean . |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Schreibgeschützt[`ICellFormat`](../icellformat) . |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Gibt die Anzahl der Grid-Spalten in der Tabelle grid der übergeordneten Tabelle zurück, die von der aktuellen Zelle aufgespannt werden sollen. Diese Eigenschaft ermöglicht es, dass cells zusammengeführt erscheint, da sie vertikale Grenzen anderer Zellen in der Tabelle überspannen. SchreibgeschütztInt32 . |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Ruft die erste Spalte der Zelle ab. Schreibgeschützt[`IColumn`](../icolumn) . |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Gibt einen Index der ersten Spalte zurück, die von der Zelle abgedeckt wird. SchreibgeschütztInt32 . |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Ruft die erste Zeile der Zelle ab. Schreibgeschützt[`IRow`](../irow) . |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Gibt einen Index der ersten Zeile zurück, die von der Zelle abgedeckt wird. SchreibgeschütztInt32 . |
| [Height](../../aspose.slides/cell/height) { get; } | Gibt die Höhe der Zelle zurück. SchreibgeschütztDouble . |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Gibt „true“ zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt wird, andernfalls „false“. SchreibgeschütztBoolean . |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Gibt die minimale Höhe einer Zelle zurück. Dies ist eine Summe der minimalen Höhen aller Zeilen, die von der Zelle verdeckt werden. SchreibgeschütztDouble . |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Gibt einen Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. SchreibgeschütztDouble . |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Gibt den Abstand von der Oberseite einer Tabelle zur Oberseite einer Zelle zurück. SchreibgeschütztDouble . |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Gibt die übergeordnete Darstellung einer Zelle zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Gibt die Anzahl der Zeilen zurück, die eine verbundene Zelle umfasst. Dies wird in Kombination mit dem vMerge-Attribut für andere Zellen verwendet, um den Anfang von cell einer horizontalen Zusammenführung anzugeben. SchreibgeschütztInt32 . |
| [Slide](../../aspose.slides/cell/slide) { get; } | Gibt die übergeordnete Folie einer Zelle zurück. Schreibgeschützt[`IBaseSlide`](../ibaseslide) . |
| [Table](../../aspose.slides/cell/table) { get; } | Gibt das übergeordnete Tabellenobjekt für eine Zelle zurück. Schreibgeschützt[`ITable`](../itable) . |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Gibt den Textankertyp zurück oder legt ihn fest. Lesen/Schreiben[`TextAnchorType`](../textanchortype) . |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Gibt den Textrahmen einer Zelle zurück. Schreibgeschützt[`ITextFrame`](../itextframe) . |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Gibt den Typ des vertikalen Textes zurück oder legt ihn fest. Lesen/Schreiben[`TextVerticalType`](../textverticaltype) . |
| [Width](../../aspose.slides/cell/width) { get; } | Gibt die Breite der Zelle zurück. SchreibgeschütztDouble . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Teilt die Zelle nach Index der Spalte in zwei Zellen auf. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Teilt die Zelle nach Index der Zeile in zwei Zellen auf. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* interface [ICell](../icell)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
