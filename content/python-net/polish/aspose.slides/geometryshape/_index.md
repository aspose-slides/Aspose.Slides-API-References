---
title: GeometryShape class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/geometryshape/
---
## GeometryShape klasa

Reprezentuje klasę bazową dla wszystkich kształtów geometrycznych.

**Dziedziczenie:**[`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ GeometryShape udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/geometryshape/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/geometryshape/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/geometryshape/custom_data/) | Zwraca własne dane kształtu.<br/>            tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/geometryshape/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/geometryshape/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/geometryshape/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/geometryshape/three_d_format/) | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/geometryshape/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/geometryshape/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/geometryshape/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy.<br/>            odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/geometryshape/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/geometryshape/hyperlink_manager/) | Zwraca menedżer hiperłączy.<br/>            tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/geometryshape/hidden/) | Określa, czy kształt jest ukryty.<br/>            odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/geometryshape/z_order_position/) | Zwraca pozycję kształtu w kolejności z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z.<br/>            tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/geometryshape/connection_site_count/) | Zwraca liczbę punktów połączenia na kształcie.<br/>            tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/geometryshape/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z.<br/>            wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/geometryshape/x/) | Pobiera lub ustawia współrzędną x lewego górnego narożnika kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/geometryshape/y/) | Pobiera lub ustawia współrzędną y lewego górnego narożnika kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/geometryshape/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/geometryshape/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/geometryshape/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego.<br/>            odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/geometryshape/unique_id/) | Zwraca wewnętrzny identyfikator o zasięgu prezentacji, przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować<br/>            jako trwały unikalny klucz.<br/>            tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/geometryshape/office_interop_shape_id/) | Zwraca unikalny identyfikator o zasięgu slajdu, który pozostaje stały przez cały okres życia kształtu i<br/>            pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie.<br/>            tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/geometryshape/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/geometryshape/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/geometryshape/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/geometryshape/is_decorative/) | Pobiera lub ustawia opcję „Oznacz jako dekoracyjne”.<br/>            odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/geometryshape/shape_lock/) | Zwraca blokady kształtu.<br/>            tylko do odczytu [`IBaseShapeLock`](/slides/python-net/pl/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/geometryshape/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/geometryshape/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/geometryshape/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/geometryshape/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pl/aspose.slides/geometryshape/shape_style/) | Zwraca obiekt stylu kształtu.<br/>            tylko do odczytu [`IShapeStyle`](/slides/python-net/pl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type/) | Zwraca lub ustawia typ predefiniowanej geometrii.<br/>            Uwaga: przy zmianie wartości wszystkie wartości dopasowania zostaną przywrócone do wartości domyślnych.<br/>            odczyt/zapis [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pl/aspose.slides/geometryshape/adjustments/) | Zwraca kolekcję wartości dopasowania kształtu.<br/>            tylko do odczytu [`IAdjustValueCollection`](/slides/python-net/pl/aspose.slides/iadjustvaluecollection). |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/geometryshape/get_image/#) | Zwraca miniaturkę kształtu.<br/>            Domyślnie używany jest typ granic miniaturki ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturkę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/geometryshape/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/geometryshape/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/geometryshape/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/geometryshape/get_geometry_paths/#) | Zwraca kopię ścieżki kształtu geometrycznego. Współrzędne są względem lewego górnego rogu kształtu. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Aktualizuje geometrię kształtu na podstawie obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego<br/>             górnego rogu kształtu.<br/>             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrię kształtu na podstawie tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego<br/>             górnego rogu kształtu.<br/>             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/geometryshape/create_shape_elements/#) | Tworzy i zwraca tablicę elementów kształtu. |

### Zobacz także
* klasa [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)