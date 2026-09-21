---
title: ICell class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/icell/
---
## ICell klasse

Vertegenwoordigt een cel in een tabel.

Het ICell-type stelt de volgende leden beschikbaar:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/nl/aspose.slides/icell/offset_x/) | Geeft een afstand van de linkerkant van een tabel tot de linkerkant van een cel.<br/>            Alleen-lezen **float**. |
| [`offset_y`](/slides/python-net/nl/aspose.slides/icell/offset_y/) | Geeft een afstand van de bovenkant van een tabel tot de bovenkant van een cel.<br/>            Alleen-lezen **float**. |
| [`first_row_index`](/slides/python-net/nl/aspose.slides/icell/first_row_index/) | Geeft een index van de eerste rij die door de cel wordt bedekt.<br/>            Alleen-lezen **int**. |
| [`first_column_index`](/slides/python-net/nl/aspose.slides/icell/first_column_index/) | Geeft een index van de eerste kolom die door de cel wordt bedekt.<br/>            Alleen-lezen **int**. |
| [`width`](/slides/python-net/nl/aspose.slides/icell/width/) | Geeft de breedte van de cel terug.<br/>            Alleen-lezen **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/icell/height/) | Geeft de hoogte van de cel terug.<br/>            Alleen-lezen **float**. |
| [`minimal_height`](/slides/python-net/nl/aspose.slides/icell/minimal_height/) | Geeft de minimumhoogte van een cel terug.<br/>            Dit is de som van de minimale hoogtes van alle rijen die door de cel worden gedekt.<br/>            Alleen-lezen **float**. |
| [`margin_left`](/slides/python-net/nl/aspose.slides/icell/margin_left/) | Geeft of stelt de linkermarge in een TextFrame in.<br/>            Lezen/schrijven **float**. |
| [`margin_right`](/slides/python-net/nl/aspose.slides/icell/margin_right/) | Geeft of stelt de rechtermarge in een TextFrame in.<br/>            Lezen/schrijven **float**. |
| [`margin_top`](/slides/python-net/nl/aspose.slides/icell/margin_top/) | Geeft of stelt de bovenmarge in een TextFrame in.<br/>            Lezen/schrijven **float**. |
| [`margin_bottom`](/slides/python-net/nl/aspose.slides/icell/margin_bottom/) | Geeft of stelt de ondermarge in een TextFrame in.<br/>            Lezen/schrijven **float**. |
| [`text_vertical_type`](/slides/python-net/nl/aspose.slides/icell/text_vertical_type/) | Geeft of stelt het type verticale tekst in.<br/>            Lezen/schrijven [`TextVerticalType`](/slides/python-net/nl/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/nl/aspose.slides/icell/text_anchor_type/) | Geeft of stelt het anker type van de tekst in.<br/>            Lezen/schrijven [`TextAnchorType`](/slides/python-net/nl/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/nl/aspose.slides/icell/anchor_center/) | Bepaalt of de tekstvak gecentreerd is binnen een cel.<br/>            Lezen/schrijven **bool**. |
| [`first_column`](/slides/python-net/nl/aspose.slides/icell/first_column/) | Haalt de eerste kolom van de cel op.<br/>            Alleen-lezen [`IColumn`](/slides/python-net/nl/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/nl/aspose.slides/icell/first_row/) | Haalt de eerste rij van de cel op.<br/>            Alleen-lezen [`IRow`](/slides/python-net/nl/aspose.slides/irow). |
| [`col_span`](/slides/python-net/nl/aspose.slides/icell/col_span/) | Geeft het aantal rasterkolommen in het tabelraster van de bovenliggende tabel terug die door de huidige cel moeten worden overspannen. Deze eigenschap maakt het mogelijk dat cellen de indruk krijgen samengevoegd te zijn, omdat ze verticale grenzen van andere cellen in de tabel overspannen.<br/>            Alleen-lezen **int**. |
| [`row_span`](/slides/python-net/nl/aspose.slides/icell/row_span/) | Geeft het aantal rijen dat een samengevoegde cel overspant. Dit wordt gebruikt in combinatie met het vMerge-attribuut van andere cellen om de begincel van een horizontale samenvoeging aan te geven.<br/>            Alleen-lezen **int**. |
| [`text_frame`](/slides/python-net/nl/aspose.slides/icell/text_frame/) | Geeft het tekstframe van een cel terug.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`table`](/slides/python-net/nl/aspose.slides/icell/table/) | Geeft het bovenliggende Table-object van een cel terug.<br/>            Alleen-lezen [`ITable`](/slides/python-net/nl/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/nl/aspose.slides/icell/is_merged_cell/) | Geeft true terug als de cel is samengevoegd met een andere aangepaste cel, anders false.<br/>            Alleen-lezen **bool**. |
| [`cell_format`](/slides/python-net/nl/aspose.slides/icell/cell_format/) | Geeft het CellFormat-object terug dat opmaak-eigenschappen voor deze cel bevat.<br/>            Alleen-lezen [`ICellFormat`](/slides/python-net/nl/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/nl/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/icell/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/nl/aspose.slides/icell/split_by_col_span/#int) | Splitst de cel in twee cellen op basis van kolomindex. |
| [`split_by_row_span(self, index)`](/slides/python-net/nl/aspose.slides/icell/split_by_row_span/#int) | Splitst de cel in twee cellen op basis van rijindex. |
| [`split_by_height(self, height)`](/slides/python-net/nl/aspose.slides/icell/split_by_height/#float) | Splitst de cel op basis van hoogte. |
| [`split_by_width(self, width)`](/slides/python-net/nl/aspose.slides/icell/split_by_width/#float) | Splitst de cel op basis van breedte. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)