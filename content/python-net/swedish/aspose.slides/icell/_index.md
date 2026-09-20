---
title: ICell class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/icell/
---
## ICell klass

Representerar en cell i en tabell.

ICell-typen visar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`offset_x`](/slides/python-net/sv/aspose.slides/icell/offset_x/) | Returnerar ett avstånd från tabellens vänstra sida till cellens vänstra sida.<br/>            Skrivskyddad **float**. |
| [`offset_y`](/slides/python-net/sv/aspose.slides/icell/offset_y/) | Returnerar ett avstånd från tabellens övre sida till cellens övre sida.<br/>            Skrivskyddad **float**. |
| [`first_row_index`](/slides/python-net/sv/aspose.slides/icell/first_row_index/) | Returnerar index för den första raden som täcks av cellen.<br/>            Skrivskyddad **int**. |
| [`first_column_index`](/slides/python-net/sv/aspose.slides/icell/first_column_index/) | Returnerar index för den första kolumnen som täcks av cellen.<br/>            Skrivskyddad **int**. |
| [`width`](/slides/python-net/sv/aspose.slides/icell/width/) | Returnerar cellens bredd.<br/>            Skrivskyddad **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/icell/height/) | Returnerar cellens höjd.<br/>            Skrivskyddad **float**. |
| [`minimal_height`](/slides/python-net/sv/aspose.slides/icell/minimal_height/) | Returnerar cellens minsta höjd.<br/>            Detta är summan av de minsta höjderna för alla rader som täcks av cellen.<br/>            Skrivskyddad **float**. |
| [`margin_left`](/slides/python-net/sv/aspose.slides/icell/margin_left/) | Returnerar eller anger den vänstra marginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_right`](/slides/python-net/sv/aspose.slides/icell/margin_right/) | Returnerar eller anger den högra marginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_top`](/slides/python-net/sv/aspose.slides/icell/margin_top/) | Returnerar eller anger den övre marginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_bottom`](/slides/python-net/sv/aspose.slides/icell/margin_bottom/) | Returnerar eller anger den nedre marginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`text_vertical_type`](/slides/python-net/sv/aspose.slides/icell/text_vertical_type/) | Returnerar eller anger typen av vertikal text.<br/>            Läs/skriv [`TextVerticalType`](/slides/python-net/sv/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/sv/aspose.slides/icell/text_anchor_type/) | Returnerar eller anger textankartypen.<br/>            Läs/skriv [`TextAnchorType`](/slides/python-net/sv/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/sv/aspose.slides/icell/anchor_center/) | Bestämmer om en textruta är centrerad i en cell eller inte.<br/>            Läs/skriv **bool**. |
| [`first_column`](/slides/python-net/sv/aspose.slides/icell/first_column/) | Hämtar cellens första kolumn.<br/>            Skrivskyddad [`IColumn`](/slides/python-net/sv/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/sv/aspose.slides/icell/first_row/) | Hämtar cellens första rad.<br/>            Skrivskyddad [`IRow`](/slides/python-net/sv/aspose.slides/irow). |
| [`col_span`](/slides/python-net/sv/aspose.slides/icell/col_span/) | Returnerar antalet rutnätskolumner i föräldratabellens rutnätsgrid som den aktuella cellen ska spänna över. Denna egenskap gör att celler kan se sammanslagna ut, eftersom de spänner över vertikala gränser för andra celler i tabellen.<br/>            Skrivskyddad **int**. |
| [`row_span`](/slides/python-net/sv/aspose.slides/icell/row_span/) | Returnerar antalet rader som en sammanslagen cell spänner över. Detta används i kombination med vMerge-attributet på andra celler för att ange startcellen för en horisontell sammanslagning.<br/>            Skrivskyddad **int**. |
| [`text_frame`](/slides/python-net/sv/aspose.slides/icell/text_frame/) | Returnerar cellens textruta.<br/>            Skrivskyddad [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`table`](/slides/python-net/sv/aspose.slides/icell/table/) | Returnerar cellens föräldra-Table-objekt.<br/>            Skrivskyddad [`ITable`](/slides/python-net/sv/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/sv/aspose.slides/icell/is_merged_cell/) | Returnerar true om cellen är sammanslagen med någon justerad cell, annars false.<br/>            Skrivskyddad **bool**. |
| [`cell_format`](/slides/python-net/sv/aspose.slides/icell/cell_format/) | Returnerar CellFormat-objektet som innehåller formateringsegenskaper för denna cell.<br/>            Skrivskyddad [`ICellFormat`](/slides/python-net/sv/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/sv/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/icell/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/sv/aspose.slides/icell/split_by_col_span/#int) | Delar cellen i två celler enligt kolumnindex. |
| [`split_by_row_span(self, index)`](/slides/python-net/sv/aspose.slides/icell/split_by_row_span/#int) | Delar cellen i två celler enligt radindex. |
| [`split_by_height(self, height)`](/slides/python-net/sv/aspose.slides/icell/split_by_height/#float) | Delar cellen efter höjd. |
| [`split_by_width(self, width)`](/slides/python-net/sv/aspose.slides/icell/split_by_width/#float) | Delar cellen efter bredd. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)