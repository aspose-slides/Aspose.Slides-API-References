---
title: ISlideCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islidecollection/
---
## ISlideCollection klass

Representerar en samling av bilder.

ISlideCollection-typen exponerar följande medlemmar:

Hämtar elementet på det angivna indexet.
            Skrivskyddad [`ISlide`](/slides/python-net/sv/aspose.slides/islide).

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/islidecollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/sv/aspose.slides/islidecollection/add_clone/#islide) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/sv/aspose.slides/islidecollection/add_clone/#islide-isection) | Lägger till en kopia av en specificerad bild i slutet av den specificerade sektionen. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/sv/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/sv/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Lägger till en kopia av en specificerad källbild i slutet av samlingen.<br/>            Lämplig layout kommer att väljas automatiskt från den specificerade <br/>            master (lämplig layout är den layout som har samma Typ eller Namn som <br/>            layouten för källbilden). Om det inte finns någon lämplig layout så<br/>            layouten för källbilden kommer att klonas (om allowCloneMissingLayout <br/>            är true) eller så kastas PptxEditException (om allowCloneMissingLayout<br/>            är false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_clone/#int-islide) | Infogar en kopia av en specificerad bild på den specificerade positionen i samlingen. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Infogar en kopia av en specificerad bild på den specificerade positionen i samlingen. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Infogar en kopia av en specificerad källbild på den specificerade positionen i samlingen.<br/>            Lämplig layout kommer att väljas automatiskt från den specificerade <br/>            master (lämplig layout är den layout som har samma Typ eller Namn som <br/>            layouten för källbilden). Om det inte finns någon lämplig layout så<br/>            layouten för källbilden kommer att klonas (om allowCloneMissingLayout <br/>            är true) eller så kastas PptxEditException (om allowCloneMissingLayout<br/>            är false). |
| [`to_array(self)`](/slides/python-net/sv/aspose.slides/islidecollection/to_array/#) | Skapar och returnerar en array med alla bilder i den. |
| [`to_array(self, start_index, count)`](/slides/python-net/sv/aspose.slides/islidecollection/to_array/#int-int) | Skapar och returnerar en array med alla bilder från det specificerade intervallet i den. |
| [`reorder(self, index, slide)`](/slides/python-net/sv/aspose.slides/islidecollection/reorder/#int-islide) | Flyttar bild från samlingen till den specificerade positionen. |
| [`reorder(self, index, slides)`](/slides/python-net/sv/aspose.slides/islidecollection/reorder/#int-listislide) | Flyttar bilder från samlingen till den specificerade positionen.<br/>            Bilderna placeras med start från index i den ordning de förekommer i listan. |
| [`add_from_pdf(self, path)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_pdf/#str) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till PDF-importalternativen. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_text)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_html/#str) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`add_from_html(self, html_stream)`](/slides/python-net/sv/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-str) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den specificerade positionen. |
| [`add_empty_slide(self, layout)`](/slides/python-net/sv/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Lägger till en ny tom bild i slutet av samlingen. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/sv/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Infogar en kopia av en specificerad bild på den specificerade positionen i samlingen. |
| [`remove(self, value)`](/slides/python-net/sv/aspose.slides/islidecollection/remove/#islide) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/islidecollection/remove_at/#int) | Tar bort elementet på det specificerade indexet i samlingen. |
| [`index_of(self, slide)`](/slides/python-net/sv/aspose.slides/islidecollection/index_of/#islide) | Returnerar ett index för den specificerade bilden i samlingen. |


### Se också
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)