---
title: AutoShape class
second_title: Aspose.Slides dla Pythona via .NET Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/autoshape/
---
## AutoShape klasa

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/pl/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

The AutoShape type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/autoshape/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/autoshape/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/autoshape/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/autoshape/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            Odczyt/Zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/autoshape/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/Zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/autoshape/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/autoshape/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/autoshape/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikseli zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektu.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/autoshape/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/autoshape/hyperlink_click/) | Zwraca lub ustawia hiperłącze określone dla kliknięcia myszą.<br/>            Odczyt/Zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/autoshape/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze określone dla najechania myszą.<br/>            Odczyt/Zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/autoshape/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/autoshape/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/Zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/autoshape/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/autoshape/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/autoshape/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/Zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/autoshape/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/autoshape/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/autoshape/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/autoshape/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/autoshape/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białym..<br/>            Odczyt/Zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/autoshape/unique_id/) | Zwraca wewnętrzny identyfikator związany z prezentacją, przeznaczony do użytku przez dodatki lub inny kod.<br/>            Ponieważ wartość tę może zostać ponownie przypisana przez użytkownika lub programowo, nie należy traktować jej jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/autoshape/office_interop_shape_id/) | Zwraca unikalny identyfikator związany ze slajdem, który pozostaje stały przez cały czas życia kształtu i pozwala PowerPointowi lub kodowi interopowi wiarygodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/autoshape/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/Zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/autoshape/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/Zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/autoshape/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Musi nie być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/Zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/autoshape/is_decorative/) | Pobiera lub ustawia opcję 'Oznacz jako dekoracyjne'<br/>            Odczyt/Zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/autoshape/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IAutoShapeLock`](/slides/python-net/pl/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/autoshape/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/autoshape/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/autoshape/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/autoshape/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pl/aspose.slides/autoshape/shape_style/) | Zwraca obiekt stylu kształtu.<br/>            Tylko do odczytu [`IShapeStyle`](/slides/python-net/pl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pl/aspose.slides/autoshape/shape_type/) | Zwraca lub ustawia typ preset geometry.<br/>            Uwaga: przy zmianie wartości wszystkie wartości regulacyjne zostaną przywrócone do ich wartości domyślnych.<br/>            Odczyt/Zapis [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pl/aspose.slides/autoshape/adjustments/) | Zwraca kolekcję wartości regulacji kształtu.<br/>            Tylko do odczytu [`IAdjustValueCollection`](/slides/python-net/pl/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/pl/aspose.slides/autoshape/auto_shape_lock/) | Zwraca blokady autoshape.<br/>            Tylko do odczytu [`IAutoShapeLock`](/slides/python-net/pl/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/pl/aspose.slides/autoshape/text_frame/) | Zwraca obiekt TextFrame dla AutoShape.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/pl/aspose.slides/autoshape/use_background_fill/) | Określa, czy ten autoshape powinien być wypełniony tłem slajdu zamiast określonym przez styl lub format wypełnienia.<br/>            Odczyt/Zapis **bool**. |
| [`is_text_box`](/slides/python-net/pl/aspose.slides/autoshape/is_text_box/) | Określa, czy kształt jest polem tekstowym. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/autoshape/get_image/#) | Zwraca miniaturę kształtu.<br/>            Typ ShapeThumbnailBounds.Shape jest używany domyślnie jako typ granic miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Zapisuje zawartość Shape jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość Shape jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/autoshape/remove_placeholder/#) | Określa, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go brak, i ustawia właściwości placeholdera na określone. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/autoshape/get_base_placeholder/#) | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu-matki, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/autoshape/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/autoshape/get_geometry_paths/#) | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względne względem lewego górnego rogu kształtu. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względne względem lewego górnego rogu kształtu.<br/>            Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względne względem lewego górnego rogu kształtu.<br/>            Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/autoshape/create_shape_elements/#) | Tworzy i zwraca tablicę elementów kształtu. |
| [`add_text_frame(self, text)`](/slides/python-net/pl/aspose.slides/autoshape/add_text_frame/#str) | Dodaje nowy TextFrame do kształtu.<br/>            Jeśli kształt już posiada TextFrame, po prostu zmienia jego tekst. |

### Zobacz także
* klasa [`AutoShape`](/slides/python-net/pl/aspose.slides/autoshape)
* klasa [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)