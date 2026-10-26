---
title: SlideCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/slidecollection/
---
## SlideCollection klasse

Stelt een verzameling van dia's voor.

Het type SlideCollection bevat de volgende leden:

Haalt het element op op de opgegeven index.
            Alleen-lezen [`Slide`](/slides/python-net/nl/aspose.slides/slide).

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides/slidecollection/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/nl/aspose.slides/slidecollection/add_clone/#islide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/nl/aspose.slides/slidecollection/add_clone/#islide-isection) | Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/nl/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/nl/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Voegt een kopie van een opgegeven brondia toe aan het einde van de collectie.<br/>            Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven <br/>            master (een geschikte lay-out is de lay-out met hetzelfde Type of Naam als <br/>            de lay-out van de brondia). Als er geen geschikte lay-out is dan<br/>            wordt de lay-out van de brondia gekloond (als allowCloneMissingLayout <br/>            true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout<br/>            false is). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_clone/#int-islide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Voegt een kopie van een opgegeven brondia in op de opgegeven positie in de collectie.<br/>            Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven <br/>            master (een geschikte lay-out is de lay-out met hetzelfde Type of Naam als <br/>            de lay-out van de brondia). Als er geen geschikte lay-out is dan<br/>            wordt de lay-out van de brondia gekloond (als allowCloneMissingLayout <br/>            true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout<br/>            false is). |
| [`to_array(self)`](/slides/python-net/nl/aspose.slides/slidecollection/to_array/#) | Maakt een array met alle dia's en retourneert deze. |
| [`to_array(self, start_index, count)`](/slides/python-net/nl/aspose.slides/slidecollection/to_array/#int-int) | Maakt een array met alle dia's uit het opgegeven bereik en retourneert deze.<br/>            Een index van de eerste toe te voegen dia. Een aantal dia's om toe te voegen. |
| [`reorder(self, index, slide)`](/slides/python-net/nl/aspose.slides/slidecollection/reorder/#int-islide) | Verplaatst een dia van de collectie naar de opgegeven positie. |
| [`reorder(self, index, slides)`](/slides/python-net/nl/aspose.slides/slidecollection/reorder/#int-listislide) | Verplaatst dia's van de collectie naar de opgegeven positie.<br/>            Dia's worden geplaatst vanaf de index in de volgorde waarin ze in de lijst verschijnen. |
| [`add_from_pdf(self, path)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_pdf/#str) | Maakt dia's aan uit het PDF-document en voegt ze toe aan het einde van de collectie. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Maakt dia's aan uit het PDF-document en voegt ze toe aan het einde van de collectie, rekening houdend met de PDF-importopties. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Maakt dia's aan uit het PDF-document en voegt ze toe aan het einde van de collectie. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Maakt dia's aan uit het PDF-document en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's aan uit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_text)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_html/#str) | Maakt dia's aan uit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's aan uit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`add_from_html(self, html_stream)`](/slides/python-net/nl/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Maakt dia's aan uit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-str) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Maakt dia's aan uit HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [`add_empty_slide(self, layout)`](/slides/python-net/nl/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Voegt een nieuwe lege dia toe aan het einde van de collectie. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/nl/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [`remove(self, value)`](/slides/python-net/nl/aspose.slides/slidecollection/remove/#islide) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/slidecollection/remove_at/#int) | Verwijdert het element op de opgegeven index van de collectie. |
| [`index_of(self, slide)`](/slides/python-net/nl/aspose.slides/slidecollection/index_of/#islide) | Retourneert een index van de opgegeven dia in de collectie. |


### Zie ook
* klasse [`Slide`](/slides/python-net/nl/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)