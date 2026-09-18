---
title: IShapeCollection class
second_title: Aspose.Slides dla Pythona przez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/
---
## IShapeCollection klasa

Reprezentuje kolekcję kształtów.

Typ IShapeCollection udostępnia następujące członków:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`parent_group`](/slides/python-net/pl/aspose.slides/ishapecollection/parent_group/) | Pobiera obiekt kształtu grupy nadrzędnej dla kolekcji kształtów.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |

Pobiera element o określonym indeksie.
            Tylko do odczytu [`IShape`](/slides/python-net/pl/aspose.slides/ishape).

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/ishapecollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, oraz dodaje<br/>            go na koniec kolekcji kształtów. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, oraz dodaje<br/>            go na koniec kolekcji kształtów. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami,<br/>            i wstawia go do kolekcji kształtów pod określonym indeksem. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami,<br/>            i wstawia go do kolekcji kształtów pod określonym indeksem. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Tworzy nową ramkę Section Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Tworzy nową ramkę Section Zoom z predefiniowanym obrazem i dodaje ją na koniec<br/>            kolekcji kształtów. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Tworzy nową ramkę Section Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec<br/>            kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów, używając<br/>            istniejącego obiektu audio z listy Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod określonym indeksem<br/>            używając istniejącego obiektu audio z listy Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/ishapecollection/to_array/#) | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/ishapecollection/to_array/#int-int) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie. |
| [`reorder(self, index, shape)`](/slides/python-net/pl/aspose.slides/ishapecollection/reorder/#int-ishape) | Przenosi określony kształt do nowej pozycji w kolekcji kształtów. |
| [`reorder(self, index, shapes)`](/slides/python-net/pl/aspose.slides/ishapecollection/reorder/#int-listishape) | Przenosi określone kształty w kolekcji kształtów, umieszczając je zaczynając od podanego indeksu. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Tworzy nowy automatyczny kształt z domyślnym formatowaniem i dodaje go na koniec<br/>            kolekcji kształtów. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Tworzy nowy automatyczny kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie<br/>            inicjalizując go domyślnym formatowaniem szablonu. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Tworzy nowy automatyczny kształt i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            stosując domyślne formatowanie szablonu. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Tworzy nowy automatyczny kształt i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            opcjonalnie inicjalizując go domyślnym stylizowaniem szablonu. |
| [`add_group_shape(self)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_group_shape/#) | Tworzy nowy pusty kształt grupowy i dodaje go na koniec kolekcji kształtów.<br/>            Ramka grupy będzie automatycznie dostosowywać się do dopasowania wszelkich dodanych do niej kształtów. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Tworzy nowy kształt grupowy, konwertuje określony obraz SVG na pojedyncze kształty,<br/>            i dodaje powstałą grupę na koniec kolekcji kształtów. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Tworzy nowy kształt łącznika z domyślnym stylowaniem szablonu i dodaje go na koniec<br/>            kolekcji kształtów. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów,<br/>            opcjonalnie stosując domyślne stylowanie szablonu. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            stosując domyślne stylowanie szablonu. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            opcjonalnie stosując domyślne stylowanie szablonu. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.<br/>            Nowy kształt zachowuje szerokość i wysokość `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_clone/#ishape) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.<br/>            Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem.<br/>            Nowy kształt zachowuje szerokość i wysokość `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem.<br/>            Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i dodaje ją na koniec kolekcji kształtów. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec<br/>            kolekcji kształtów. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`index_of(self, shape)`](/slides/python-net/pl/aspose.slides/ishapecollection/index_of/#ishape) | Zwraca indeks zerowy pierwszego wystąpienia określonego kształtu w kolekcji. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Tworzy nowy prostokątny kształt automatyczny do prezentacji treści matematycznej i dodaje go na koniec<br/>            kolekcji kształtów. |
| [`insert_group_shape(self, index)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_group_shape/#int) | Tworzy nowy pusty kształt grupowy i wstawia go do kolekcji kształtów pod określonym indeksem.<br/>            Ramka grupy będzie automatycznie dostosowywać się do dopasowania wszelkich dodanych do niej kształtów. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na koniec<br/>            kolekcji kształtów. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/pl/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/pl/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/ishapecollection/remove_at/#int) | Usuwa kształt pod określonym indeksem z kolekcji kształtów. |
| [`remove(self, shape)`](/slides/python-net/pl/aspose.slides/ishapecollection/remove/#ishape) | Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides/ishapecollection/clear/#) | Usuwa wszystkie kształty z kolekcji kształtów. |


### Zobacz także
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)