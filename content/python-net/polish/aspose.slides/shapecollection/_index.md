---
title: ShapeCollection class
second_title: Aspose.Slides dla Pythona – odwołanie do API .NET
description: 
type: docs
url: /pl/aspose.slides/shapecollection/
---
## ShapeCollection klasa

Reprezentuje kolekcję kształtów.

Typ ShapeCollection udostępnia następujące członki.

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`parent_group`](/slides/python-net/pl/aspose.slides/shapecollection/parent_group/) | Pobiera obiekt grupy kształtów nadrzędny dla kolekcji kształtów.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |

Pobiera element o określonym indeksie.
            Tylko do odczytu [`IShape`](/slides/python-net/pl/aspose.slides/ishape).

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/shapecollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Tworzy nowy wykres, inicjalizuje go danymi przykładowych serii i ustawieniami, a następnie dodaje<br/>            go na koniec kolekcji kształtów. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/pl/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Tworzy nowy wykres, inicjalizuje go danymi przykładowych serii i ustawieniami, a następnie dodaje<br/>            go na koniec kolekcji kształtów. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Tworzy nowy wykres, inicjalizuje go danymi przykładowych serii i ustawieniami,<br/>            i wstawia go do kolekcji kształtów pod określonym indeksem. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Tworzy nowy wykres, inicjalizuje go danymi przykładowych serii i ustawieniami,<br/>            i wstawia go do kolekcji kształtów pod określonym indeksem. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/pl/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/pl/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Tworzy nową ramkę Zoom z wstępnie zdefiniowanym obrazem i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/pl/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Tworzy nową ramkę Section Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/pl/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Tworzy nową ramkę Section Zoom z wstępnie zdefiniowanym obrazem i dodaje ją na koniec kolekcji kształtów. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Tworzy nową ramkę Section Zoom z wstępnie zdefiniowanym obrazem i wstawia ją do<br/>            kolekcji kształtów pod określonym indeksem. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/pl/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/pl/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/pl/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/pl/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec<br/>            kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/pl/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów, używając<br/>            istniejącego obiektu audio z listy Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod określonym indeksem<br/>            używając istniejącego obiektu audio z listy Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/shapecollection/to_array/#) | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/shapecollection/to_array/#int-int) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie. |
| [`reorder(self, index, shape)`](/slides/python-net/pl/aspose.slides/shapecollection/reorder/#int-ishape) | Przenosi określony kształt do nowej pozycji w kolekcji kształtów. |
| [`reorder(self, index, shapes)`](/slides/python-net/pl/aspose.slides/shapecollection/reorder/#int-listishape) | Przenosi określone kształty w kolekcji kształtów, umieszczając je począwszy od podanego indeksu. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec<br/>            kolekcji kształtów. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie<br/>            inicjalizując go domyślnym formatowaniem szablonu. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            stosując domyślne formatowanie szablonu. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            opcjonalnie inicjalizując go domyślnym stylem szablonu. |
| [`add_group_shape(self)`](/slides/python-net/pl/aspose.slides/shapecollection/add_group_shape/#) | Tworzy nową pustą grupę kształtów i dodaje ją na koniec kolekcji kształtów.<br/>            Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie dodane do niej kształty. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Tworzy nową grupę kształtów, konwertuje określony obraz SVG na poszczególne kształty,<br/>            i dodaje powstałą grupę na koniec kolekcji kształtów. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Tworzy nowy kształt łącznika z domyślnym stylem szablonu i dodaje go na koniec<br/>            kolekcji kształtów. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów,<br/>            opcjonalnie stosując domyślny styl szablonu. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            stosując domyślny styl szablonu. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem,<br/>            opcjonalnie stosując domyślny styl szablonu. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/pl/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.<br/>            Nowy kształt zachowuje szerokość i wysokość `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/pl/aspose.slides/shapecollection/add_clone/#ishape) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.<br/>            Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem.<br/>            Nowy kształt zachowuje szerokość i wysokość `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_clone/#int-ishape) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod określonym indeksem.<br/>            Sklonowany kształt zachowuje pozycję i rozmiar oryginału. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/pl/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i dodaje ją na koniec kolekcji kształtów. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Tworzy nową ramkę audio powiązaną z ścieżką CD i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec<br/>            kolekcji kształtów. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`index_of(self, shape)`](/slides/python-net/pl/aspose.slides/shapecollection/index_of/#ishape) | Zwraca indeks zerowy pierwszego wystąpienia określonego kształtu w kolekcji. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/pl/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Tworzy nowy prostokątny auto-kształt do przechowywania treści matematycznej i dodaje go na koniec<br/>            kolekcji kształtów. |
| [`insert_group_shape(self, index)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_group_shape/#int) | Tworzy nową pustą grupę kształtów i wstawia ją do kolekcji kształtów pod określonym indeksem.<br/>            Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie dodane do niej kształty. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/pl/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na koniec<br/>            kolekcji kształtów. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów<br/>            pod określonym indeksem. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/pl/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/pl/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów pod określonym indeksem. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/shapecollection/remove_at/#int) | Usuwa kształt o określonym indeksie z kolekcji kształtów. |
| [`remove(self, shape)`](/slides/python-net/pl/aspose.slides/shapecollection/remove/#ishape) | Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides/shapecollection/clear/#) | Usuwa wszystkie kształty z kolekcji kształtów. |


### Zobacz także
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)