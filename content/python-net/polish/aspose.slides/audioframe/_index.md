---
title: AudioFrame class
second_title: Aspose.Slides dla Pythona via .NET - odniesienie do API
description: 
type: docs
url: /pl/aspose.slides/audioframe/
---
## AudioFrame klasa

Reprezentuje klip audio na slajdzie.

**Inheritance:**[`AudioFrame`](/slides/python-net/pl/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ AudioFrame udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/audioframe/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/audioframe/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/audioframe/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/audioframe/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/audioframe/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/audioframe/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie posiadają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/audioframe/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie posiadają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/audioframe/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikseli stosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie posiadają właściwości efektu.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/audioframe/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie posiadają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/audioframe/hyperlink_click/) | Zwraca lub ustawia hiperłącze definiowane dla kliknięcia myszy.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/audioframe/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze definiowane dla najechania myszy.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/audioframe/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/audioframe/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/audioframe/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/audioframe/connection_site_count/) | Zwraca liczbę punktów połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/audioframe/rotation/) | Zwraca lub ustawia liczbę stopni, o którą podany kształt jest obrócony wokół osi Z.<br/>            Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/audioframe/x/) | Zwraca lub ustawia współrzędną x lewego górnego rogu kształtu, wyrażoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/audioframe/y/) | Zwraca lub ustawia współrzędną y lewego górnego rogu kształtu, wyrażoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/audioframe/width/) | Zwraca lub ustawia szerokość kształtu, wyrażoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/audioframe/height/) | Zwraca lub ustawia wysokość kształtu, wyrażoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/audioframe/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym.<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/audioframe/unique_id/) | Zwraca wewnętrzny identyfikator związany z prezentacją przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/audioframe/office_interop_shape_id/) | Zwraca unikalny identyfikator powiązany z slajdem, który pozostaje stały przez cały okres życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/audioframe/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/audioframe/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/audioframe/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nazwa nie może być None. W razie potrzeby użyj pustego ciągu.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/audioframe/is_decorative/) | Zwraca lub ustawia opcję „Mark as decorative”.<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/audioframe/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IPictureFrameLock`](/slides/python-net/pl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/audioframe/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/audioframe/parent_group/) | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/audioframe/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/audioframe/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pl/aspose.slides/audioframe/shape_style/) | Zwraca obiekt stylu kształtu.<br/>            Tylko do odczytu [`IShapeStyle`](/slides/python-net/pl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pl/aspose.slides/audioframe/shape_type/) | Zwraca lub ustawia typ AutoShape dla PictureFrame.<br/>            Dozwolone są wszystkie elementy zbioru [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype), z wyjątkiem następujących typów linii:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Odczyt/zapis [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pl/aspose.slides/audioframe/adjustments/) | Zwraca kolekcję wartości regulacji kształtu.<br/>            Tylko do odczytu [`IAdjustValueCollection`](/slides/python-net/pl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/pl/aspose.slides/audioframe/picture_frame_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IPictureFrameLock`](/slides/python-net/pl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/pl/aspose.slides/audioframe/picture_format/) | Zwraca obiekt PictureFillFormat dla ramki obrazu.<br/>            Tylko do odczytu [`IPictureFillFormat`](/slides/python-net/pl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/pl/aspose.slides/audioframe/relative_scale_height/) | Zwraca lub ustawia skalę wysokości (względną do oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100 %.<br/>            Odczyt/zapis **float**. |
| [`relative_scale_width`](/slides/python-net/pl/aspose.slides/audioframe/relative_scale_width/) | Zwraca lub ustawia skalę szerokości (względną do oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100 %.<br/>            Odczyt/zapis **float**. |
| [`is_cameo`](/slides/python-net/pl/aspose.slides/audioframe/is_cameo/) | Określa, czy PictureFrame jest obiektem Cameo czy nie.<br/>            Tylko do odczytu **bool**. |
| [`audio_cd_start_track`](/slides/python-net/pl/aspose.slides/audioframe/audio_cd_start_track/) | Zwraca lub ustawia indeks początkowego śladu.<br/>            Odczyt/zapis **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/pl/aspose.slides/audioframe/audio_cd_start_track_time/) | Zwraca lub ustawia czas początkowego śladu.<br/>            Odczyt/zapis **int**. |
| [`audio_cd_end_track`](/slides/python-net/pl/aspose.slides/audioframe/audio_cd_end_track/) | Zwraca lub ustawia indeks ostatniego śladu.<br/>            Odczyt/zapis **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/pl/aspose.slides/audioframe/audio_cd_end_track_time/) | Zwraca lub ustawia czas ostatniego śladu.<br/>            Odczyt/zapis **int**. |
| [`volume`](/slides/python-net/pl/aspose.slides/audioframe/volume/) | Zwraca lub ustawia głośność dźwięku.<br/>            Odczyt/zapis [`AudioVolumeMode`](/slides/python-net/pl/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/pl/aspose.slides/audioframe/play_mode/) | Zwraca lub ustawia tryb odtwarzania dźwięku.<br/>            Odczyt/zapis [`AudioPlayModePreset`](/slides/python-net/pl/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/pl/aspose.slides/audioframe/hide_at_showing/) | Określa, czy AudioFrame jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`play_loop_mode`](/slides/python-net/pl/aspose.slides/audioframe/play_loop_mode/) | Określa, czy dźwięk jest zapętlony.<br/>            Odczyt/zapis **bool**. |
| [`play_across_slides`](/slides/python-net/pl/aspose.slides/audioframe/play_across_slides/) | Określa, czy dźwięk odtwarzany jest na wszystkich slajdach.<br/>            Odczyt/zapis **bool**. |
| [`rewind_audio`](/slides/python-net/pl/aspose.slides/audioframe/rewind_audio/) | Określa, czy dźwięk jest automatycznie przewijany do początku po odtworzeniu.<br/>            Odczyt/zapis **bool**. |
| [`embedded`](/slides/python-net/pl/aspose.slides/audioframe/embedded/) | Określa, czy dźwięk jest osadzony w prezentacji.<br/>            Tylko do odczytu **bool**. |
| [`link_path_long`](/slides/python-net/pl/aspose.slides/audioframe/link_path_long/) | Zwraca lub ustawia nazwę pliku audio powiązanego z AudioFrame.<br/>            Odczyt/zapis **str**. |
| [`embedded_audio`](/slides/python-net/pl/aspose.slides/audioframe/embedded_audio/) | Zwraca lub ustawia osadzony obiekt audio.<br/>            Odczyt/zapis [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/pl/aspose.slides/audioframe/fade_in_duration/) | Określa czas trwania początkowego zanikania mediów w milisekundach.<br/>            Odczyt/zapis **float**. |
| [`fade_out_duration`](/slides/python-net/pl/aspose.slides/audioframe/fade_out_duration/) | Określa czas trwania końcowego zanikania mediów w milisekundach.<br/>            Odczyt/zapis **float**. |
| [`volume_value`](/slides/python-net/pl/aspose.slides/audioframe/volume_value/) | Zwraca lub ustawia głośność dźwięku w procentach.<br/>            Odczyt/zapis **float**. |
| [`trim_from_start`](/slides/python-net/pl/aspose.slides/audioframe/trim_from_start/) | Określa czas trwania, który ma być usunięty z początku mediów podczas odtwarzania, w milisekundach.<br/>            Odczyt/zapis **float**. |
| [`trim_from_end`](/slides/python-net/pl/aspose.slides/audioframe/trim_from_end/) | Określa czas trwania, który ma być usunięty z końca mediów podczas odtwarzania, w milisekundach.<br/>            Odczyt/zapis **float**. |
| [`caption_tracks`](/slides/python-net/pl/aspose.slides/audioframe/caption_tracks/) | Zwraca kolekcję napisów zamkniętych powiązanych z ramką audio.<br/>            Ta właściwość jest tylko do odczytu i zwraca [`ICaptionsCollection`](/slides/python-net/pl/aspose.slides/icaptionscollection) zawierający wszystkie ścieżki napisów. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/audioframe/get_image/#) | Zwraca miniaturę kształtu.<br/>            Typ ShapeThumbnailBounds.Shape jest używany domyślnie. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/audioframe/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na wskazany. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/audioframe/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu-mistrza, z którego aktualny kształt jest dziedziczony).<br/>            Zwraca None, jeśli aktualny kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/audioframe/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/audioframe/get_geometry_paths/#) | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względem lewego górnego rogu kształtu. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu.<br/>            Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu.<br/>            Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/audioframe/create_shape_elements/#) | Tworzy i zwraca tablicę elementów kształtu. |

### Zobacz także
* klasa [`AudioFrame`](/slides/python-net/pl/aspose.slides/audioframe)
* klasa [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape)
* klasa [`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)