---
title: SlideCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/slidecollection/
---
## SlideCollection klass

Representerar en samling av bilder.

SlideCollection-typen exponerar följande medlemmar:

Hämtar elementet på det specificerade indexet.
            Skrivskyddad [`Slide`](/slides/python-net/sv/aspose.slides/slide).

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/slidecollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/sv/aspose.slides/slidecollection/add_clone/#islide) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/sv/aspose.slides/slidecollection/add_clone/#islide-isection) | Lägger till en kopia av en specificerad bild i slutet av den specificerade sektionen. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/sv/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/sv/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Lägger till en kopia av en specificerad källbild i slutet av samlingen.<br/>            Lämplig layout kommer att väljas automatiskt från den specificerade <br/>            master (lämplig layout är den layout som har samma Type eller Name som <br/>            layouten för källbilden). Om det inte finns någon lämplig layout så<br/>            layouten för källbilden kommer att klonas (om allowCloneMissingLayout <br/>            är true) eller PptxEditException kommer att kastas (om allowCloneMissingLayout<br/>            är false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_clone/#int-islide) | Infogar en kopia av en specificerad bild på en specificerad position i samlingen. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Infogar en kopia av en specificerad bild på en specificerad position i samlingen. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Infogar en kopia av en specificerad källbild på en specificerad position i samlingen.<br/>            Lämplig layout kommer att väljas automatiskt från den specificerade <br/>            master (lämplig layout är den layout som har samma Type eller Name som <br/>            layouten för källbilden). Om det inte finns någon lämplig layout så<br/>            layouten för källbilden kommer att klonas (om allowCloneMissingLayout <br/>            är true) eller PptxEditException kommer att kastas (om allowCloneMissingLayout<br/>            är false). |
| [`to_array(self)`](/slides/python-net/sv/aspose.slides/slidecollection/to_array/#) | Skapar och returnerar en array med alla bilder i den. |
| [`to_array(self, start_index, count)`](/slides/python-net/sv/aspose.slides/slidecollection/to_array/#int-int) | Skapar och returnerar en array med alla bilder från det specificerade intervallet i den.<br/>            Ett index för den första bilden att lägga till.Ett antal bilder att lägga till. |
| [`reorder(self, index, slide)`](/slides/python-net/sv/aspose.slides/slidecollection/reorder/#int-islide) | Flyttar bild från samlingen till den specificerade positionen. |
| [`reorder(self, index, slides)`](/slides/python-net/sv/aspose.slides/slidecollection/reorder/#int-listislide) | Flyttar bilder från samlingen till den specificerade positionen.<br/>            Bilderna placeras med start från index i den ordning de förekommer i listan. |
| [`add_from_pdf(self, path)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_pdf/#str) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med beaktande av pdf-importalternativen. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_text)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_html/#str) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_stream)`](/slides/python-net/sv/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-str) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`add_empty_slide(self, layout)`](/slides/python-net/sv/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Lägger till en ny tom bild i slutet av samlingen. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/sv/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Infogar en kopia av en specificerad bild på en specificerad position i samlingen. |
| [`remove(self, value)`](/slides/python-net/sv/aspose.slides/slidecollection/remove/#islide) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/slidecollection/remove_at/#int) | Tar bort elementet på det specificerade indexet i samlingen. |
| [`index_of(self, slide)`](/slides/python-net/sv/aspose.slides/slidecollection/index_of/#islide) | Returnerar ett index för den specificerade bilden i samlingen. |

### Se även
* klass [`Slide`](/slides/python-net/sv/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)