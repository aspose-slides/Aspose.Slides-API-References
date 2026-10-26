---
title: ISlideCollection class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API
description: 
type: docs
url: /pl/aspose.slides/islidecollection/
---
## ISlideCollection klasa

Reprezentuje kolekcję slajdów.

Typ ISlideCollection udostępnia następujące elementy:

Pobiera element pod określonym indeksem.  
            Tylko do odczytu [`ISlide`](/slides/python-net/pl/aspose.slides/islide).

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/islidecollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/pl/aspose.slides/islidecollection/add_clone/#islide) | Dodaje kopię określonego slajdu na końcu kolekcji. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/pl/aspose.slides/islidecollection/add_clone/#islide-isection) | Dodaje kopię określonego slajdu na końcu określonej sekcji. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/pl/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Dodaje kopię określonego slajdu na końcu kolekcji. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pl/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Dodaje kopię określonego slajdu źródłowego na końcu kolekcji.<br/>            Odpowiedni układ zostanie wybrany automatycznie z określonego <br/>            mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co <br/>            układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, <br/>            układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout <br/>            jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout <br/>            jest false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_clone/#int-islide) | Wstawia kopię określonego slajdu na określoną pozycję w kolekcji. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Wstawia kopię określonego slajdu na określoną pozycję w kolekcji. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Wstawia kopię określonego slajdu źródłowego na określoną pozycję w kolekcji.<br/>            Odpowiedni układ zostanie wybrany automatycznie z określonego <br/>            mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co <br/>            układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, <br/>            układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout <br/>            jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout <br/>            jest false). |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/islidecollection/to_array/#) | Tworzy i zwraca tablicę zawierającą wszystkie slajdy. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/islidecollection/to_array/#int-int) | Tworzy i zwraca tablicę zawierającą wszystkie slajdy z określonego zakresu. |
| [`reorder(self, index, slide)`](/slides/python-net/pl/aspose.slides/islidecollection/reorder/#int-islide) | Przenosi slajd z kolekcji na określoną pozycję. |
| [`reorder(self, index, slides)`](/slides/python-net/pl/aspose.slides/islidecollection/reorder/#int-listislide) | Przenosi slajdy z kolekcji na określoną pozycję.<br/>            Slajdy zostaną umieszczone zaczynając od indeksu w kolejności, w jakiej występują na liście. |
| [`add_from_pdf(self, path)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_pdf/#str) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_text)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_html/#str) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_stream)`](/slides/python-net/pl/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-str) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`add_empty_slide(self, layout)`](/slides/python-net/pl/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Dodaje nowy pusty slajd na koniec kolekcji. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/pl/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Wstawia kopię określonego slajdu na określoną pozycję w kolekcji. |
| [`remove(self, value)`](/slides/python-net/pl/aspose.slides/islidecollection/remove/#islide) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/islidecollection/remove_at/#int) | Usuwa element pod określonym indeksem w kolekcji. |
| [`index_of(self, slide)`](/slides/python-net/pl/aspose.slides/islidecollection/index_of/#islide) | Zwraca indeks określonego slajdu w kolekcji. |

### Zobacz także
* klasa [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)