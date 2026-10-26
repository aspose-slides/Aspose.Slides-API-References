---
title: ISlideCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islidecollection/
---
## ISlideCollection klasse

Stelt een collectie van dia's voor.

Het type ISlideCollection geeft de volgende leden weer:

Haalt het element op op de opgegeven index.
            Alleen-lezen [`ISlide`](/slides/python-net/nl/aspose.slides/islide).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides/islidecollection/__getitem__/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/nl/aspose.slides/islidecollection/add_clone/#islide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/nl/aspose.slides/islidecollection/add_clone/#islide-isection) | Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/nl/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/nl/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie.<br/>            Een geschikt layout wordt automatisch geselecteerd uit de opgegeven <br/>            master (een geschikt layout is het layout met hetzelfde Type of Naam als <br/>            het layout van de bron-dia). Als er geen geschikt layout is dan<br/>            wordt het layout van de bron-dia gekloond (als allowCloneMissingLayout <br/>            true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout<br/>            false is). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_clone/#int-islide) | Voegt een kopie van een opgegeven dia in op een opgegeven positie in de collectie. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Voegt een kopie van een opgegeven dia in op een opgegeven positie in de collectie. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Voegt een kopie van een opgegeven bron-dia in op een opgegeven positie in de collectie.<br/>            Een geschikt layout wordt automatisch geselecteerd uit de opgegeven <br/>            master (een geschikt layout is het layout met hetzelfde Type of Naam als <br/>            het layout van de bron-dia). Als er geen geschikt layout is dan<br/>            wordt het layout van de bron-dia gekloond (als allowCloneMissingLayout <br/>            true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout<br/>            false is). |
| [`to_array(self)`](/slides/python-net/nl/aspose.slides/islidecollection/to_array/#) | Maakt een array met alle dia's en retourneert deze. |
| [`to_array(self, start_index, count)`](/slides/python-net/nl/aspose.slides/islidecollection/to_array/#int-int) | Maakt een array met alle dia's uit het opgegeven bereik en retourneert deze. |
| [`reorder(self, index, slide)`](/slides/python-net/nl/aspose.slides/islidecollection/reorder/#int-islide) | Verplaatst een dia uit de collectie naar de opgegeven positie. |
| [`reorder(self, index, slides)`](/slides/python-net/nl/aspose.slides/islidecollection/reorder/#int-listislide) | Verplaatst dia's uit de collectie naar de opgegeven positie.<br/>            Dia's worden geplaatst beginnend vanaf de index in de volgorde waarin ze in de lijst verschijnen. |
| [`add_from_pdf(self, path)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_pdf/#str) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie, rekening houdend met de pdf-importopties. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_text)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_html/#str) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_stream)`](/slides/python-net/nl/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-str) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`add_empty_slide(self, layout)`](/slides/python-net/nl/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Voegt een nieuwe lege dia toe aan het einde van de collectie. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/nl/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Voegt een kopie van een opgegeven dia in op een opgegeven positie in de collectie. |
| [`remove(self, value)`](/slides/python-net/nl/aspose.slides/islidecollection/remove/#islide) | Verwijdert de eerste voorkomen van een specifiek object uit de collectie. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/islidecollection/remove_at/#int) | Verwijdert het element op de opgegeven index uit de collectie. |
| [`index_of(self, slide)`](/slides/python-net/nl/aspose.slides/islidecollection/index_of/#islide) | Retourneert een index van de opgegeven dia in de collectie. |

### Zie ook
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)