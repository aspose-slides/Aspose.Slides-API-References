---
title: Cell
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een cel van een tabel voor.
type: docs
weight: 1130
url: /nl/aspose.slides/cell/
---
## Cell klasse

Stelt een cel van een tabel voor.

```csharp
public class Cell : ICell
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. Lezen/schrijven Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Retourneert het CellFormat-object dat opmaak-eigenschappen voor deze cel bevat. Alleen-lezen [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Retourneert het aantal rasterkolommen in het tabelraster van de bovenliggende tabel dat door de huidige cel wordt overspannen. Deze eigenschap maakt het mogelijk dat cellen de indruk krijgen samengevoegd te zijn, omdat ze verticale grenzen van andere cellen in de tabel overspannen. Alleen-lezen Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Haalt de eerste kolom van de cel op. Alleen-lezen [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Retourneert een index van de eerste kolom die door de cel wordt gedekt. Alleen-lezen Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Haalt de eerste rij van de cel op. Alleen-lezen [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Retourneert een index van de eerste rij die door de cel wordt gedekt. Alleen-lezen Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Retourneert de hoogte van de cel. Alleen-lezen Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. Alleen-lezen Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Retourneert of stelt de ondermarge in een TextFrame in. Lezen/schrijven Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Retourneert of stelt de linkermarge in een TextFrame in. Lezen/schrijven Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Retourneert of stelt de rechtermarge in een TextFrame in. Lezen/schrijven Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Retourneert of stelt de bovengrens in een TextFrame in. Lezen/schrijven Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Retourneert de minimumhoogte van een cel. Dit is de som van de minimale hoogtes van alle rijen die door de cel worden gedekt. Alleen-lezen Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. Alleen-lezen Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. Alleen-lezen Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Retourneert de bovenliggende presentatie van een cel. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Retourneert het aantal rijen dat een samengevoegde cel overspant. Dit wordt in combinatie met het vMerge-attribuut op andere cellen gebruikt om de begincel van een horizontale samenvoeging te specificeren. Alleen-lezen Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Retourneert de bovenliggende dia van een cel. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Retourneert het bovenliggende Table-object voor een cel. Alleen-lezen [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Retourneert of stelt het tekstankertype in. Lezen/schrijven [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Retourneert het tekstframe van een cel. Alleen-lezen [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Retourneert of stelt het type verticale tekst in. Lezen/schrijven [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Retourneert de breedte van de cel. Alleen-lezen Double. |

## Methoden

| Name | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Splitst de cel in twee cellen op basis van de kolomindex. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Splitst de cel op basis van de hoogte. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Splitst de cel in twee cellen op basis van de rij-index. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Splitst de cel op basis van de breedte. |

### Zie ook

* interface [ICell](../icell)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->