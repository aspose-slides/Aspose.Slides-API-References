---
title: ZoomObject class
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides/zoomobject/
---
## klasa ZoomObject

Reprezentuje obiekt Zoom na slajdzie.

**Inheritance:**[`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ ZoomObject udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/zoomobject/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/zoomobject/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/zoomobject/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/zoomobject/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/zoomobject/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/zoomobject/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/zoomobject/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/zoomobject/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/zoomobject/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/zoomobject/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/zoomobject/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/zoomobject/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/zoomobject/hidden/) | Określa, czy kształt jest ukryty.<br/>            odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/zoomobject/z_order_position/) | Zwraca pozycję kształtu w kolejności z-order.<br/>            Shapes[0] zwraca kształt znajdujący się na końcu kolejności z-order,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się na początku kolejności z-order.<br/>            tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/zoomobject/connection_site_count/) | Zwraca liczbę punktów połączeń na kształcie.<br/>            tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/zoomobject/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z.<br/>            dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny.<br/>            odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/zoomobject/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, wyrażoną w punktach.<br/>            odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/zoomobject/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, wyrażoną w punktach.<br/>            odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/zoomobject/width/) | Pobiera lub ustawia szerokość kształtu, wyrażoną w punktach.<br/>            odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/zoomobject/height/) | Pobiera lub ustawia wysokość kształtu, wyrażoną w punktach.<br/>            odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/zoomobject/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym.<br/>            odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/zoomobject/unique_id/) | Zwraca wewnętrzny identyfikator powiązany z prezentacją, przeznaczony do użytku przez dodatki lub inny kod.<br/>            Ponieważ wartość tę można zmienić przez użytkownika lub programowo, nie powinna być traktowana jako trwały unikalny klucz.<br/>            tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/zoomobject/office_interop_shape_id/) | Zwraca unikalny identyfikator przypisany do slajdu, który pozostaje stały przez cały okres życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/zoomobject/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/zoomobject/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/zoomobject/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/zoomobject/is_decorative/) | Pobiera lub ustawia opcję „Mark as decorative”.<br/>            odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/zoomobject/shape_lock/) | Zwraca blokady kształtu.<br/>            tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/zoomobject/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/zoomobject/parent_group/) | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/zoomobject/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/zoomobject/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/zoomobject/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/pl/aspose.slides/zoomobject/image_type/) | Pobiera lub ustawia typ obrazu obiektu Zoom.<br/>            odczyt/zapis [`ZoomImageType`](/slides/python-net/pl/aspose.slides/zoomimagetype).<br/>            Wartość domyślna: Preview |
| [`return_to_parent`](/slides/python-net/pl/aspose.slides/zoomobject/return_to_parent/) | Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów.<br/>            odczyt/zapis **bool**.<br/>            Wartość domyślna: false |
| [`show_background`](/slides/python-net/pl/aspose.slides/zoomobject/show_background/) | Pobiera lub ustawia wartość określającą, czy Zoom będzie używać tła docelowego slajdu.<br/>            odczyt/zapis **bool**.<br/>            Wartość domyślna: true |
| [`zoom_image`](/slides/python-net/pl/aspose.slides/zoomobject/zoom_image/) | Pobiera lub ustawia obraz dla obiektu Zoom.<br/>            odczyt/zapis [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/pl/aspose.slides/zoomobject/transition_duration/) | Pobiera lub ustawia czas trwania przejścia między Zoom a slajdem.<br/>            odczyt/zapis **float**.<br/>            Wartość domyślna: 1.0f |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/zoomobject/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/zoomobject/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go brak, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/zoomobject/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/zoomobject/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)