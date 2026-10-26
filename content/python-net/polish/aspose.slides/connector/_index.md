---
title: Connector class
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/connector/
---
## Klasa Connector

Reprezentuje łącznik.

**Inheritance:**[`Connector`](/slides/python-net/pl/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

The Connector type exposes the following members:

## Properties

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/connector/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/connector/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/connector/custom_data/) | Zwraca dane niestandardowe kształtu.<br/>            tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/connector/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/connector/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/connector/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/connector/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/connector/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/connector/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/connector/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/connector/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/connector/hyperlink_manager/) | Zwraca menedżer hiperłącza.<br/>            tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/connector/hidden/) | Określa, czy kształt jest ukryty.<br/>            odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/connector/z_order_position/) | Zwraca pozycję kształtu w kolejności z-order.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z-order,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z-order.<br/>            tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/connector/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/connector/rotation/) | Zwraca lub ustawia liczbę stopni, o które podany kształt jest obrócony wokół osi z.<br/>            Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/connector/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/connector/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/connector/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/connector/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/connector/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego.<br/>            odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/connector/unique_id/) | Zwraca wewnętrzny identyfikator powiązany z prezentacją, przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość tę można ponownie przypisać przez użytkownika lub programowo, nie należy traktować<br/>            jej jako trwałego unikalnego klucza.<br/>            tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/connector/office_interop_shape_id/) | Zwraca unikalny identyfikator związany ze slajdem, który pozostaje stały przez cały okres życia kształtu i<br/>            umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/connector/alternative_text/) | Zwraca lub ustawia alternatywny tekst powiązany z kształtem.<br/>            odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/connector/alternative_text_title/) | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem.<br/>            odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/connector/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego łańcucha znaków.<br/>            odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/connector/is_decorative/) | Pobiera lub ustawia opcję 'Mark as decorative'.<br/>            odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/connector/shape_lock/) | Zwraca blokady kształtu.<br/>            tylko do odczytu [`IConnectorLock`](/slides/python-net/pl/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/connector/is_grouped/) | Określa, czy kształt jest zgrupowany.<br/>            tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/connector/parent_group/) | Zwraca obiekt nadrzędnego GroupShape, jeśli kształt jest zgrupowany. W przeciwnym razie zwraca None.<br/>            tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/connector/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/connector/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pl/aspose.slides/connector/shape_style/) | Zwraca obiekt stylu kształtu.<br/>            tylko do odczytu [`IShapeStyle`](/slides/python-net/pl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pl/aspose.slides/connector/shape_type/) | Zwraca lub ustawia typ AutoShape.<br/>            odczyt/zapis [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pl/aspose.slides/connector/adjustments/) | Zwraca kolekcję wartości dopasowania kształtu.<br/>            tylko do odczytu [`IAdjustValueCollection`](/slides/python-net/pl/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/pl/aspose.slides/connector/connector_lock/) | Zwraca blokady łącznika.<br/>            tylko do odczytu [`IConnectorLock`](/slides/python-net/pl/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/pl/aspose.slides/connector/start_shape_connected_to/) | Zwraca lub ustawia kształt, do którego przyczepia się początek łącznika.<br/>            odczyt/zapis [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/pl/aspose.slides/connector/end_shape_connected_to/) | Zwraca lub ustawia kształt, do którego przyczepia się koniec łącznika.<br/>            odczyt/zapis [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/pl/aspose.slides/connector/start_shape_connection_site_index/) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu początkowego.<br/>            odczyt/zapis **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/pl/aspose.slides/connector/end_shape_connection_site_index/) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu końcowego.<br/>            odczyt/zapis **int**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/connector/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/connector/write_as_svg/#iorawiobase) | Zapisuje zawartość Shape jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość Shape jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/connector/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/connector/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określone. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/connector/get_base_placeholder/#) | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/connector/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/connector/get_geometry_paths/#) | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względne względem lewego górnego rogu kształtu. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/connector/set_geometry_path/#igeometrypath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względne względem lewego<br/>             górnego rogu kształtu.<br/>             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względne względem lewego<br/>             górnego rogu kształtu.<br/>             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/connector/create_shape_elements/#) | Tworzy i zwraca tablicę elementów kształtu. |
| [`reroute(self)`](/slides/python-net/pl/aspose.slides/connector/reroute/#) | Przebija łącznik tak, aby przyjął najkrótszą możliwą ścieżkę pomiędzy kształtami, które łączy. |

### Zobacz także
* klasa [`Connector`](/slides/python-net/pl/aspose.slides/connector)
* klasa [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)