---
title: ISlideCollection class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/islidecollection/
---
## ISlideCollection Klasse

Stellt eine Sammlung von Folien dar.

Der ISlideCollection-Typ stellt die folgenden Member bereit:

Liefert das Element am angegebenen Index.
            Nur lesbar [`ISlide`](/slides/python-net/de/aspose.slides/islide).

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/islidecollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/de/aspose.slides/islidecollection/add_clone/#islide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/de/aspose.slides/islidecollection/add_clone/#islide-isection) | Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/de/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/de/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu.<br/>            Das passende Layout wird automatisch aus dem angegebenen <br/>            Master ausgewählt (ein passendes Layout ist das Layout mit demselben Typ oder Namen wie <br/>            das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, <br/>            wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout <br/>            true ist) oder eine PptxEditException ausgelöst (wenn allowCloneMissingLayout <br/>            false ist). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/de/aspose.slides/islidecollection/insert_clone/#int-islide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/de/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/de/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position in die Sammlung ein.<br/>            Das passende Layout wird automatisch aus dem angegebenen <br/>            Master ausgewählt (ein passendes Layout ist das Layout mit demselben Typ oder Namen wie <br/>            das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, <br/>            wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout <br/>            true ist) oder eine PptxEditException ausgelöst (wenn allowCloneMissingLayout <br/>            false ist). |
| [`to_array(self)`](/slides/python-net/de/aspose.slides/islidecollection/to_array/#) | Erstellt ein Array mit allen Folien und gibt es zurück. |
| [`to_array(self, start_index, count)`](/slides/python-net/de/aspose.slides/islidecollection/to_array/#int-int) | Erstellt ein Array mit allen Folien aus dem angegebenen Bereich und gibt es zurück. |
| [`reorder(self, index, slide)`](/slides/python-net/de/aspose.slides/islidecollection/reorder/#int-islide) | Verschiebt die Folie aus der Sammlung an die angegebene Position. |
| [`reorder(self, index, slides)`](/slides/python-net/de/aspose.slides/islidecollection/reorder/#int-listislide) | Verschiebt Folien aus der Sammlung an die angegebene Position.<br/>            Folien werden beginnend beim Index in der Reihenfolge, in der sie in der Liste erscheinen, platziert. |
| [`add_from_pdf(self, path)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_pdf/#str) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu, wobei die PDF-Importoptionen berücksichtigt werden. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [`add_from_html(self, html_text)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_html/#str) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [`add_from_html(self, html_stream)`](/slides/python-net/de/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-str) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/de/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [`add_empty_slide(self, layout)`](/slides/python-net/de/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Fügt eine neue leere Folie am Ende der Sammlung hinzu. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/de/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [`remove(self, value)`](/slides/python-net/de/aspose.slides/islidecollection/remove/#islide) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/islidecollection/remove_at/#int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [`index_of(self, slide)`](/slides/python-net/de/aspose.slides/islidecollection/index_of/#islide) | Gibt den Index der angegebenen Folie in der Sammlung zurück. |

### Siehe auch
* Klasse [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)