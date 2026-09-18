---
title: ZoomFrame class
second_title: Aspose.Slides dla Pythona - referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/zoomframe/
---
## Klasa ZoomFrame

Reprezentuje obiekt Slide Zoom na slajdzie.

**Dziedziczenie:**[`ZoomFrame`](/slides/python-net/pl/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ ZoomFrame udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/zoomframe/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/zoomframe/placeholder/) | Zwraca symbol zastępczy dla kształtu. Zwraca None, jeśli kształt nie ma symbolu zastępczego.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/zoomframe/custom_data/) | Zwraca dane niestandardowe kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/zoomframe/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/zoomframe/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/zoomframe/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/zoomframe/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/zoomframe/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/zoomframe/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/zoomframe/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/zoomframe/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania kursorem myszki.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/zoomframe/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/zoomframe/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/zoomframe/z_order_position/) | Zwraca pozycję kształtu w kolejności z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/zoomframe/connection_site_count/) | Zwraca liczbę punktów połączenia na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/zoomframe/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół<br/>            osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/zoomframe/x/) | Zwraca lub ustawia współrzędną x lewego górnego rogu kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/zoomframe/y/) | Zwraca lub ustawia współrzędną y lewego górnego rogu kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/zoomframe/width/) | Zwraca lub ustawia szerokość kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/zoomframe/height/) | Zwraca lub ustawia wysokość kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/zoomframe/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego..<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/zoomframe/unique_id/) | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować<br/>            jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/zoomframe/office_interop_shape_id/) | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i<br/>            pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/zoomframe/alternative_text/) | Zwraca lub ustawia tekst alternatywny związany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/zoomframe/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego związanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/zoomframe/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/zoomframe/is_decorative/) | Zwraca lub ustawia opcję 'Mark as decorative'.<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/zoomframe/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/zoomframe/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/zoomframe/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/zoomframe/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/zoomframe/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/zoomframe/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/pl/aspose.slides/zoomframe/image_type/) | Zwraca lub ustawia typ obrazu obiektu zoom.<br/>            Odczyt/zapis [`ZoomImageType`](/slides/python-net/pl/aspose.slides/zoomimagetype).<br/>            Domyślna wartość: Preview |
| [`return_to_parent`](/slides/python-net/pl/aspose.slides/zoomframe/return_to_parent/) | Zwraca lub ustawia zachowanie nawigacji w pokazie slajdów.<br/>            Odczyt/zapis **bool**.<br/>            Domyślna wartość: false |
| [`show_background`](/slides/python-net/pl/aspose.slides/zoomframe/show_background/) | Zwraca lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu.<br/>            Odczyt/zapis **bool**.<br/>            Domyślna wartość: true |
| [`zoom_image`](/slides/python-net/pl/aspose.slides/zoomframe/zoom_image/) | Zwraca lub ustawia obraz dla obiektu zoom.<br/>            Odczyt/zapis [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/pl/aspose.slides/zoomframe/transition_duration/) | Zwraca lub ustawia czas trwania przejścia między Zoom a slajdem.<br/>            Odczyt/zapis **float**.<br/>            Domyślna wartość: 1.0f |
| [`target_slide`](/slides/python-net/pl/aspose.slides/zoomframe/target_slide/) | Zwraca lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom.<br/>            Odczyt/zapis [`ISlide`](/slides/python-net/pl/aspose.slides/islide). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/zoomframe/get_image/#) | Zwraca miniaturkę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniaturki kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturkę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/zoomframe/remove_placeholder/#) | Definiuje, że ten kształt nie jest symbolem zastępczym. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Dodaje nowy symbol zastępczy, jeśli go brak, i ustawia właściwości symbolu zastępczego na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/zoomframe/get_base_placeholder/#) | Zwraca podstawowy kształt symbolu zastępczego (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/zoomframe/get_visual_bounds/#) | Zwraca wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`ZoomFrame`](/slides/python-net/pl/aspose.slides/zoomframe)
* klasa [`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)