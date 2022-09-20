---
title: ICell
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert eine Zelle in einer Tabelle.
type: docs
weight: 4980
url: /de/net/aspose.slides/icell/
---
## ICell interface

Repräsentiert eine Zelle in einer Tabelle.

```csharp
public interface ICell : ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lesen/SchreibenBoolean . |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Ermöglicht das Abrufen der Basis-ISlideComponent-Schnittstelle. Schreibgeschützt[`ISlideComponent`](../islidecomponent) . |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Schreibgeschützt[`ICellFormat`](../icellformat) . |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Gibt die Anzahl der Grid-Spalten in der Tabelle grid der übergeordneten Tabelle zurück, die von der aktuellen Zelle aufgespannt werden sollen. Diese Eigenschaft ermöglicht es, dass cells zusammengeführt erscheint, da sie vertikale Grenzen anderer Zellen in der Tabelle überspannen. SchreibgeschütztInt32 . |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Ruft die erste Spalte der Zelle ab. Schreibgeschützt[`IColumn`](../icolumn) . |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Gibt einen Index der ersten Spalte zurück, die von der Zelle abgedeckt wird. SchreibgeschütztInt32 . |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Ruft die erste Zeile der Zelle ab. Schreibgeschützt[`IRow`](../irow) . |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Gibt einen Index der ersten Zeile zurück, die von der Zelle abgedeckt wird. SchreibgeschütztInt32 . |
| [Height](../../aspose.slides/icell/height) { get; } | Gibt die Höhe der Zelle zurück. SchreibgeschütztDouble . |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Gibt „true“ zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt wird, andernfalls „false“. SchreibgeschütztBoolean . |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. Lesen/SchreibenDouble . |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Gibt die minimale Höhe einer Zelle zurück. Dies ist eine Summe der minimalen Höhen aller Zeilen, die von der Zelle verdeckt werden. SchreibgeschütztDouble . |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Gibt einen Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. SchreibgeschütztDouble . |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Gibt den Abstand von der Oberseite einer Tabelle zur Oberseite einer Zelle zurück. SchreibgeschütztDouble . |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Gibt die Anzahl der Zeilen zurück, die eine verbundene Zelle umfasst. Dies wird in Kombination mit dem vMerge-Attribut für andere Zellen verwendet, um den Anfang von cell einer horizontalen Zusammenführung anzugeben. SchreibgeschütztInt32 . |
| [Table](../../aspose.slides/icell/table) { get; } | Gibt das übergeordnete Tabellenobjekt für eine Zelle zurück. Schreibgeschützt[`ITable`](../itable) . |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Gibt den Textankertyp zurück oder legt ihn fest. Lesen/Schreiben[`TextAnchorType`](../textanchortype) . |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Gibt den Textrahmen einer Zelle zurück. Schreibgeschützt[`ITextFrame`](../itextframe) . |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Gibt den Typ des vertikalen Textes zurück oder legt ihn fest. Lesen/Schreiben[`TextVerticalType`](../textverticaltype) . |
| [Width](../../aspose.slides/icell/width) { get; } | Gibt die Breite der Zelle zurück. SchreibgeschütztDouble . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Teilt die Zelle nach Index der Spalte in zwei Zellen auf. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Teilt die Zelle nach Höhe. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Teilt die Zelle nach Index der Zeile in zwei Zellen auf. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Teilt die Zelle nach Breite. |

### Siehe auch

* interface [ISlideComponent](../islidecomponent)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
