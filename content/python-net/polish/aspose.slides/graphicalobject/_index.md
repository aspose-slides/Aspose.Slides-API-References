---
title: GraphicalObject class
second_title: Aspose.Slides dla Pythona via .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/graphicalobject/
---
## GraphicalObject klasa

Represents abstract graphical object.

**Inheritance:**[`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

The GraphicalObject type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/graphicalobject/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/graphicalobject/placeholder/) | Zwraca element zastępczy dla kształtu. Zwraca None, jeśli kształt nie ma elementu zastępczego.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/graphicalobject/custom_data/) | Zwraca dane niestandardowe kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/graphicalobject/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            Odczyt/Zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/graphicalobject/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/Zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/graphicalobject/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/graphicalobject/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/graphicalobject/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/graphicalobject/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/graphicalobject/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy.<br/>            Odczyt/Zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/Zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/graphicalobject/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/graphicalobject/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/Zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/graphicalobject/z_order_position/) | Zwraca pozycję kształtu w kolejności z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/graphicalobject/connection_site_count/) | Zwraca liczbę punktów połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/graphicalobject/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z.<br/>            Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/Zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/graphicalobject/x/) | Zwraca lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/graphicalobject/y/) | Zwraca lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/graphicalobject/width/) | Zwraca lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/graphicalobject/height/) | Zwraca lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/Zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/graphicalobject/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego..<br/>            Odczyt/Zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/graphicalobject/unique_id/) | Zwraca wewnętrzny identyfikator ograniczony do prezentacji, przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować<br/>            jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/graphicalobject/office_interop_shape_id/) | Zwraca unikalny identyfikator ograniczony do slajdu, który pozostaje stały przez cały okres życia kształtu i<br/>            pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/graphicalobject/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/Zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/graphicalobject/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/Zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/graphicalobject/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/Zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/graphicalobject/is_decorative/) | Zwraca lub ustawia opcję 'Mark as decorative'<br/>            Odczyt/Zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/graphicalobject/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/graphicalobject/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/graphicalobject/parent_group/) | Zwraca obiekt rodzica GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/graphicalobject/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/graphicalobject/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/graphicalobject/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/graphicalobject/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Zapisuje zawartość Shape jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość Shape jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/graphicalobject/remove_placeholder/#) | Określa, że ten kształt nie jest elementem zastępczym. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Dodaje nowy element zastępczy, jeśli go nie ma, i ustawia właściwości elementu zastępczego na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/graphicalobject/get_base_placeholder/#) | Zwraca podstawowy kształt elementu zastępczego (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/graphicalobject/get_visual_bounds/#) | Pobiera granice wizualne kształtu obliczone na podstawie jego renderowanej zawartości. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)