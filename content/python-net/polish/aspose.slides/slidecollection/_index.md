---
title: SlideCollection class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/slidecollection/
---
## SlideCollection klasa

Reprezentuje kolekcję slajdów.

Typ SlideCollection udostępnia następujące członków:

Pobiera element pod określonym indeksem.
            Tylko do odczytu [`Slide`](/slides/python-net/pl/aspose.slides/slide).

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/slidecollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/pl/aspose.slides/slidecollection/add_clone/#islide) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/pl/aspose.slides/slidecollection/add_clone/#islide-isection) | Dodaje kopię określonego slajdu na koniec określonej sekcji. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/pl/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pl/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Dodaje kopię określonego slajdu źródłowego na koniec kolekcji.<br/>            Odpowiedni layout zostanie wybrany automatycznie z określonego <br/>            master (odpowiedni layout to layout o tym samym Type lub Name jako <br/>            layout slajdu źródłowego). Jeśli nie ma odpowiedniego layoutu, <br/>            layout slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout <br/>            jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout <br/>            jest false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_clone/#int-islide) | Wstawia kopię określonego slajdu na określoną pozycję w kolekcji. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Wstawia kopię określonego slajdu na określoną pozycję w kolekcji. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Dodaje kopię określonego slajdu źródłowego na określoną pozycję w kolekcji.<br/>            Odpowiedni layout zostanie wybrany automatycznie z określonego <br/>            master (odpowiedni layout to layout o tym samym Type lub Name jako <br/>            layout slajdu źródłowego). Jeśli nie ma odpowiedniego layoutu, <br/>            layout slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout <br/>            jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout <br/>            jest false). |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/slidecollection/to_array/#) | Tworzy i zwraca tablicę ze wszystkimi slajdami. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/slidecollection/to_array/#int-int) | Tworzy i zwraca tablicę ze wszystkimi slajdami z określonego zakresu.<br/>            Indeks pierwszego slajdu do dodania. Liczba slajdów do dodania. |
| [`reorder(self, index, slide)`](/slides/python-net/pl/aspose.slides/slidecollection/reorder/#int-islide) | Przenosi slajd z kolekcji na określoną pozycję. |
| [`reorder(self, index, slides)`](/slides/python-net/pl/aspose.slides/slidecollection/reorder/#int-listislide) | Przenosi slajdy z kolekcji na określoną pozycję.<br/>            Slajdy będą umieszczane począwszy od indeksu w kolejności, w jakiej występują na liście. |
| [`add_from_pdf(self, path)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_pdf/#str) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_text)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_html/#str) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`add_from_html(self, html_stream)`](/slides/python-net/pl/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-str) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określoną pozycję. |
| [`add_empty_slide(self, layout)`](/slides/python-net/pl/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Dodaje nowy pusty slajd na koniec kolekcji. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/pl/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Wstawia kopię określonego slajdu na określoną pozycję w kolekcji. |
| [`remove(self, value)`](/slides/python-net/pl/aspose.slides/slidecollection/remove/#islide) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/slidecollection/remove_at/#int) | Usuwa element pod określonym indeksem w kolekcji. |
| [`index_of(self, slide)`](/slides/python-net/pl/aspose.slides/slidecollection/index_of/#islide) | Zwraca indeks określonego slajdu w kolekcji. |

### Zobacz także
* klasa [`Slide`](/slides/python-net/pl/aspose.slides/slide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)