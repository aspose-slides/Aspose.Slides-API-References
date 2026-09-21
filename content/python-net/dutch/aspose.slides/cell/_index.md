---
title: Cell class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/cell/
---
## Cell klasse

Stelt een cel van een tabel voor.

Het Cell-type exposeert de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/nl/aspose.slides/cell/offset_x/) | Geeft een afstand van de linkerkant van een tabel tot de linkerkant van een cel.<br/>            Alleen-lezen **float**. |
| [`offset_y`](/slides/python-net/nl/aspose.slides/cell/offset_y/) | Geeft een afstand van de bovenkant van een tabel tot de bovenkant van een cel.<br/>            Alleen-lezen **float**. |
| [`first_row_index`](/slides/python-net/nl/aspose.slides/cell/first_row_index/) | Geeft de index van de eerste rij die door de cel wordt gedekt.<br/>            Alleen-lezen **int**. |
| [`first_column_index`](/slides/python-net/nl/aspose.slides/cell/first_column_index/) | Geeft de index van de eerste kolom die door de cel wordt gedekt.<br/>            Alleen-lezen **int**. |
| [`width`](/slides/python-net/nl/aspose.slides/cell/width/) | Geeft de breedte van de cel.<br/>            Alleen-lezen **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/cell/height/) | Geeft de hoogte van de cel.<br/>            Alleen-lezen **float**. |
| [`minimal_height`](/slides/python-net/nl/aspose.slides/cell/minimal_height/) | Geeft de minimale hoogte van een cel.<br/>            Dit is de som van de minimale hoogtes van alle rijen die door de cel worden gedekt.<br/>            Alleen-lezen **float**. |
| [`margin_left`](/slides/python-net/nl/aspose.slides/cell/margin_left/) | Geeft of stelt de linkermarge in een TextFrame in.<br/>            Lezen/Schrijven **float**. |
| [`margin_right`](/slides/python-net/nl/aspose.slides/cell/margin_right/) | Geeft of stelt de rechtermarge in een TextFrame in.<br/>            Lezen/Schrijven **float**. |
| [`margin_top`](/slides/python-net/nl/aspose.slides/cell/margin_top/) | Geeft of stelt de bovenmarge in een TextFrame in.<br/>            Lezen/Schrijven **float**. |
| [`margin_bottom`](/slides/python-net/nl/aspose.slides/cell/margin_bottom/) | Geeft of stelt de ondermarge in een TextFrame in.<br/>            Lezen/Schrijven **float**. |
| [`text_vertical_type`](/slides/python-net/nl/aspose.slides/cell/text_vertical_type/) | Geeft of stelt het type verticale tekst in.<br/>            Lezen/Schrijven [`TextVerticalType`](/slides/python-net/nl/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/nl/aspose.slides/cell/text_anchor_type/) | Geeft of stelt het anker type van de tekst in.<br/>            Lezen/Schrijven [`TextAnchorType`](/slides/python-net/nl/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/nl/aspose.slides/cell/anchor_center/) | Bepaalt of een tekstvak al dan niet gecentreerd is binnen een cel.<br/>            Lezen/Schrijven **bool**. |
| [`first_row`](/slides/python-net/nl/aspose.slides/cell/first_row/) | Haalt de eerste rij van de cel op.<br/>            Alleen-lezen [`IRow`](/slides/python-net/nl/aspose.slides/irow). |
| [`first_column`](/slides/python-net/nl/aspose.slides/cell/first_column/) | Haalt de eerste kolom van de cel op.<br/>            Alleen-lezen [`IColumn`](/slides/python-net/nl/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/nl/aspose.slides/cell/col_span/) | Geeft het aantal rasterkolommen in het tabelraster van de bovenliggende tabel dat door de huidige cel wordt overspannen.<br/>            Deze eigenschap maakt het mogelijk dat cellen de uitstraling hebben van samengevoegd te zijn, aangezien ze verticale grenzen van andere cellen in de tabel overspannen.<br/>            Alleen-lezen **int**. |
| [`row_span`](/slides/python-net/nl/aspose.slides/cell/row_span/) | Geeft het aantal rijen dat een samengevoegde cel overspant. Dit wordt in combinatie gebruikt<br/>            met het vMerge-attribuut op andere cellen om de begincel van een horizontale samenvoeging te specificeren.<br/>            Alleen-lezen **int**. |
| [`text_frame`](/slides/python-net/nl/aspose.slides/cell/text_frame/) | Geeft het tekstkader van een cel.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`table`](/slides/python-net/nl/aspose.slides/cell/table/) | Geeft het bovenliggende Table-object voor een cel.<br/>            Alleen-lezen [`ITable`](/slides/python-net/nl/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/nl/aspose.slides/cell/is_merged_cell/) | Geeft true terug als de cel is samengevoegd met een aangepaste cel, anders false.<br/>            Alleen-lezen **bool**. |
| [`cell_format`](/slides/python-net/nl/aspose.slides/cell/cell_format/) | Geeft het CellFormat-object dat opmaak-eigenschappen voor deze cel bevat.<br/>            Alleen-lezen [`ICellFormat`](/slides/python-net/nl/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/nl/aspose.slides/cell/slide/) | Geeft de bovenliggende dia van een cel.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/cell/presentation/) | Geeft de bovenliggende presentatie van een cel.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |

## Methoden

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/nl/aspose.slides/cell/split_by_col_span/#int) | Splits de cel in twee cellen op basis van de kolomindex. |
| [`split_by_row_span(self, index)`](/slides/python-net/nl/aspose.slides/cell/split_by_row_span/#int) | Splits de cel in twee cellen op basis van de rij-index. |
| [`split_by_height(self, height)`](/slides/python-net/nl/aspose.slides/cell/split_by_height/#float) | Splits de cel op hoogte. |
| [`split_by_width(self, width)`](/slides/python-net/nl/aspose.slides/cell/split_by_width/#float) | Splits de cel op breedte. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)