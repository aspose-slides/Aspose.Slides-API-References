---
title: VideoFrame class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/videoframe/
---
## VideoFrame klasa

Reprezentuje klip wideo na slajdzie.

**Dziedziczenie:**[`VideoFrame`](/slides/python-net/pl/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ VideoFrame udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/videoframe/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/videoframe/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/videoframe/custom_data/) | Zwraca własne dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/videoframe/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/videoframe/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/videoframe/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/videoframe/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/videoframe/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/videoframe/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/videoframe/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/videoframe/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/videoframe/hyperlink_manager/) | Zwraca menedżer hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/videoframe/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/videoframe/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/videoframe/connection_site_count/) | Zwraca liczbę punktów połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/videoframe/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z.<br/>            Dodatnia wartość oznacza obrót zgodnie z ruchem wskazówek zegara; ujemna wartość<br/>            oznacza obrót przeciwnie do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/videoframe/x/) | Pobiera lub ustawia współrzędną x lewego górnego narożnika kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/videoframe/y/) | Pobiera lub ustawia współrzędną y lewego górnego narożnika kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/videoframe/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/videoframe/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/videoframe/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego..<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/videoframe/unique_id/) | Zwraca wewnętrzny, w zakresie prezentacji identyfikator przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość tę można ponownie przypisać przez użytkownika lub programowo, nie należy traktować<br/>            jako trwały unikalny klucz.<br/>            Tylko do odczytu **int**.<br/>            Zobacz również [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/videoframe/office_interop_shape_id/) | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały okres życia kształtu i<br/>            umożliwia PowerPointowi lub kodowi interopowy niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz również [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/videoframe/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/videoframe/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/videoframe/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/videoframe/is_decorative/) | Pobiera lub ustawia opcję 'Oznacz jako dekoracyjny'<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/videoframe/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IPictureFrameLock`](/slides/python-net/pl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/videoframe/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/videoframe/parent_group/) | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/videoframe/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/videoframe/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pl/aspose.slides/videoframe/shape_style/) | Zwraca obiekt stylu kształtu.<br/>            Tylko do odczytu [`IShapeStyle`](/slides/python-net/pl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pl/aspose.slides/videoframe/shape_type/) | Zwraca lub ustawia typ AutoShape dla PictureFrame.<br/>            Dozwolone są wszystkie elementy ze zbioru [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype), <br/>            z wyjątkiem wszystkich rodzajów linii:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Odczyt/zapis [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pl/aspose.slides/videoframe/adjustments/) | Zwraca kolekcję wartości dopasowania kształtu.<br/>            Tylko do odczytu [`IAdjustValueCollection`](/slides/python-net/pl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/pl/aspose.slides/videoframe/picture_frame_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IPictureFrameLock`](/slides/python-net/pl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/pl/aspose.slides/videoframe/picture_format/) | Zwraca obiekt PictureFillFormat dla ramki obrazu.<br/>            Tylko do odczytu [`IPictureFillFormat`](/slides/python-net/pl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/pl/aspose.slides/videoframe/relative_scale_height/) | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100%.<br/>            Odczyt/zapis **float**. |
| [`relative_scale_width`](/slides/python-net/pl/aspose.slides/videoframe/relative_scale_width/) | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100%.<br/>            Odczyt/zapis **float**. |
| [`is_cameo`](/slides/python-net/pl/aspose.slides/videoframe/is_cameo/) | Określa, czy PictureFrame jest obiektem Cameo, czy nie.<br/>            Tylko do odczytu **bool**. |
| [`rewind_video`](/slides/python-net/pl/aspose.slides/videoframe/rewind_video/) | Określa, czy wideo jest automatycznie przewijane do początku<br/>            zaraz po zakończeniu odtwarzania filmu.<br/>            Odczyt/zapis **bool**. |
| [`play_loop_mode`](/slides/python-net/pl/aspose.slides/videoframe/play_loop_mode/) | Określa, czy wideo jest zapętlone.<br/>            Odczyt/zapis **bool**. |
| [`hide_at_showing`](/slides/python-net/pl/aspose.slides/videoframe/hide_at_showing/) | Określa, czy VideoFrame jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`volume`](/slides/python-net/pl/aspose.slides/videoframe/volume/) | Zwraca lub ustawia głośność audio.<br/>            Odczyt/zapis [`AudioVolumeMode`](/slides/python-net/pl/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/pl/aspose.slides/videoframe/play_mode/) | Zwraca lub ustawia tryb odtwarzania wideo.<br/>            Odczyt/zapis [`VideoPlayModePreset`](/slides/python-net/pl/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/pl/aspose.slides/videoframe/full_screen_mode/) | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym.<br/>            Odczyt/zapis **bool**. |
| [`link_path_long`](/slides/python-net/pl/aspose.slides/videoframe/link_path_long/) | Zwraca lub ustawia nazwę pliku wideo, który jest powiązany z VideoFrame.<br/>            Odczyt/zapis **str**. |
| [`embedded_video`](/slides/python-net/pl/aspose.slides/videoframe/embedded_video/) | Zwraca lub ustawia osadzony obiekt wideo.<br/>            Odczyt/zapis [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/pl/aspose.slides/videoframe/trim_from_start/) | Początek przycięcia [ms] |
| [`trim_from_end`](/slides/python-net/pl/aspose.slides/videoframe/trim_from_end/) | Koniec przycięcia [ms] |
| [`caption_tracks`](/slides/python-net/pl/aspose.slides/videoframe/caption_tracks/) | Pobiera kolekcję zamkniętych napisów powiązanych z ramką wideo.<br/>             Ta właściwość jest tylko do odczytu i zwraca [`ICaptionsCollection`](/slides/python-net/pl/aspose.slides/icaptionscollection) zawierający wszystkie ścieżki napisów. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/videoframe/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniatury. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/videoframe/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/videoframe/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/videoframe/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/videoframe/get_geometry_paths/#) | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względem lewego górnego narożnika kształtu. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego<br/>             górnego narożnika kształtu.<br/>             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego<br/>             górnego narożnika kształtu.<br/>             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/videoframe/create_shape_elements/#) | Tworzy i zwraca tablicę elementów kształtu. |

### Zobacz także
* klasa [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape)
* klasa [`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`VideoFrame`](/slides/python-net/pl/aspose.slides/videoframe)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)