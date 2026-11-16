---
title: ICell
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een cel in een tabel voor.
type: docs
weight: 5470
url: /nl/aspose.slides/icell/
---
## ICell interface

Stelt een cel in een tabel voor.

```csharp
public interface ICell : ISlideComponent
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Bepaalt of een tekstvak gecentreerd is binnen een cel. Lezen/Schrijven Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Stelt u in staat de basis-ISlideComponent-interface op te halen. Alleen-lezen [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Retourneert het CellFormat-object dat opmaak-eigenschappen voor deze cel bevat. Alleen-lezen [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Retourneert het aantal rasterkolommen in het tabelraster van de bovenliggende tabel dat door de huidige cel moet worden overspannen. Deze eigenschap maakt het mogelijk dat cellen de uitstraling hebben samengevoegd te zijn, doordat ze verticale grenzen van andere cellen in de tabel overspannen. Alleen-lezen Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Haalt de eerste kolom van de cel op. Alleen-lezen [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Retourneert de index van de eerste kolom die door de cel wordt bedekt. Alleen-lezen Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Haalt de eerste rij van de cel op. Alleen-lezen [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Retourneert de index van de eerste rij die door de cel wordt bedekt. Alleen-lezen Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Retourneert de hoogte van de cel. Alleen-lezen Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. Alleen-lezen Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Retourneert of stelt de onderste marge in een TextFrame in. Lezen/Schrijven Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Retourneert of stelt de linkermarge in een TextFrame in. Lezen/Schrijven Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Retourneert of stelt de rechtermarge in een TextFrame in. Lezen/Schrijven Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Retourneert of stelt de bovenmarge in een TextFrame in. Lezen/Schrijven Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Retourneert de minimale hoogte van een cel. Dit is de som van de minimale hoogtes van alle rijen die door de cel worden bedekt. Alleen-lezen Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Retourneert de afstand van de linkerkant van een tabel tot de linkerkant van een cel. Alleen-lezen Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Retourneert de afstand van de bovenkant van een tabel tot de bovenkant van een cel. Alleen-lezen Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Retourneert het aantal rijen dat een samengevoegde cel overspant. Dit wordt in combinatie met het vMerge-attribuut op andere cellen gebruikt om de begincel van een horizontale samenvoeging te specificeren. Alleen-lezen Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Retourneert het bovenliggende Table-object voor een cel. Alleen-lezen [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Retourneert of stelt het type tekstankerpunt in. Lezen/Schrijven [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Retourneert het tekstframe van een cel. Alleen-lezen [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Retourneert of stelt het type verticale tekst in. Lezen/Schrijven [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Retourneert de breedte van de cel. Alleen-lezen Double. |

## Methoden

| Name | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Splitst de cel in twee cellen op basis van de kolomindex. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Splitst de cel op hoogte. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Splitst de cel in twee cellen op basis van de rij-index. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Splitst de cel op breedte. |

### Zie ook

* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->