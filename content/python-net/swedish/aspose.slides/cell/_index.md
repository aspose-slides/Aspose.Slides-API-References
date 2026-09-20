---
title: Cell class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/cell/
---
## Cell-klass

Representerar en cell i en tabell.

Cell-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`offset_x`](/slides/python-net/sv/aspose.slides/cell/offset_x/) | Returnerar ett avstånd från vänstra sidan av en tabell till vänstra sidan av en cell.<br/>            Skrivskyddad **float**. |
| [`offset_y`](/slides/python-net/sv/aspose.slides/cell/offset_y/) | Returnerar ett avstånd från övre sidan av en tabell till övre sidan av en cell.<br/>            Skrivskyddad **float**. |
| [`first_row_index`](/slides/python-net/sv/aspose.slides/cell/first_row_index/) | Returnerar ett index för första raden som täcks av cellen.<br/>            Skrivskyddad **int**. |
| [`first_column_index`](/slides/python-net/sv/aspose.slides/cell/first_column_index/) | Returnerar ett index för första kolumnen som täcks av cellen.<br/>            Skrivskyddad **int**. |
| [`width`](/slides/python-net/sv/aspose.slides/cell/width/) | Returnerar cellens bredd.<br/>            Skrivskyddad **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/cell/height/) | Returnerar cellens höjd.<br/>            Skrivskyddad **float**. |
| [`minimal_height`](/slides/python-net/sv/aspose.slides/cell/minimal_height/) | Returnerar den minsta höjden för en cell.<br/>            Detta är en summa av minimihöjderna för alla rader som täcks av cellen.<br/>            Skrivskyddad **float**. |
| [`margin_left`](/slides/python-net/sv/aspose.slides/cell/margin_left/) | Returnerar eller anger vänstermarginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_right`](/slides/python-net/sv/aspose.slides/cell/margin_right/) | Returnerar eller anger högermarginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_top`](/slides/python-net/sv/aspose.slides/cell/margin_top/) | Returnerar eller anger toppmarginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`margin_bottom`](/slides/python-net/sv/aspose.slides/cell/margin_bottom/) | Returnerar eller anger bottenmarginalen i en TextFrame.<br/>            Läs/skriv **float**. |
| [`text_vertical_type`](/slides/python-net/sv/aspose.slides/cell/text_vertical_type/) | Returnerar eller anger typen av vertikal text.<br/>            Läs/skriv [`TextVerticalType`](/slides/python-net/sv/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/sv/aspose.slides/cell/text_anchor_type/) | Returnerar eller anger textankringstypen.<br/>            Läs/skriv [`TextAnchorType`](/slides/python-net/sv/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/sv/aspose.slides/cell/anchor_center/) | Bestämmer om textrutan är centrerad i cellen eller inte.<br/>            Läs/skriv **bool**. |
| [`first_row`](/slides/python-net/sv/aspose.slides/cell/first_row/) | Hämtar första raden i cellen.<br/>            Skrivskyddad [`IRow`](/slides/python-net/sv/aspose.slides/irow). |
| [`first_column`](/slides/python-net/sv/aspose.slides/cell/first_column/) | Hämtar första kolumnen i cellen.<br/>            Skrivskyddad [`IColumn`](/slides/python-net/sv/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/sv/aspose.slides/cell/col_span/) | Returnerar antalet rutnätskolumner i föräldertabellens tabellrutnät som ska omfattas av den aktuella cellen. Denna egenskap gör att celler kan ha utseendet av att vara sammanslagna, eftersom de spänner över vertikala gränser för andra celler i tabellen.<br/>            Skrivskyddad **int**. |
| [`row_span`](/slides/python-net/sv/aspose.slides/cell/row_span/) | Returnerar antalet rader som en sammanslagen cell omfattar. Detta används i kombination med vMerge-attributet på andra celler för att ange startcellen för en horisontell sammanslagning.<br/>            Skrivskyddad **int**. |
| [`text_frame`](/slides/python-net/sv/aspose.slides/cell/text_frame/) | Returnerar textramen för en cell.<br/>            Skrivskyddad [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`table`](/slides/python-net/sv/aspose.slides/cell/table/) | Returnerar föräldra-Table-objektet för en cell.<br/>            Skrivskyddad [`ITable`](/slides/python-net/sv/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/sv/aspose.slides/cell/is_merged_cell/) | Returnerar true om cellen är sammanslagen med någon justerad cell, annars false.<br/>            Skrivskyddad **bool**. |
| [`cell_format`](/slides/python-net/sv/aspose.slides/cell/cell_format/) | Returnerar CellFormat-objektet som innehåller formateringsegenskaper för denna cell.<br/>            Skrivskyddad [`ICellFormat`](/slides/python-net/sv/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/sv/aspose.slides/cell/slide/) | Returnerar föräldra-slide för en cell.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/cell/presentation/) | Returnerar föräldrapresentationen för en cell.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/sv/aspose.slides/cell/split_by_col_span/#int) | Delar cellen i två celler efter kolumnindex. |
| [`split_by_row_span(self, index)`](/slides/python-net/sv/aspose.slides/cell/split_by_row_span/#int) | Delar cellen i två celler efter radindex. |
| [`split_by_height(self, height)`](/slides/python-net/sv/aspose.slides/cell/split_by_height/#float) | Delar cellen efter höjd. |
| [`split_by_width(self, width)`](/slides/python-net/sv/aspose.slides/cell/split_by_width/#float) | Delar cellen efter bredd. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)