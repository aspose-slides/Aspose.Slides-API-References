---
title: SmartArt class
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.smartart/smartart/
---
## Klasa SmartArt

Reprezentuje diagram SmartArt

**Dziedziczenie:**[`SmartArt`](/slides/python-net/pl/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ SmartArt udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides.smartart/smartart/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides.smartart/smartart/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides.smartart/smartart/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides.smartart/smartart/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides.smartart/smartart/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides.smartart/smartart/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides.smartart/smartart/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides.smartart/smartart/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides.smartart/smartart/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides.smartart/smartart/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania kursorem.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides.smartart/smartart/hyperlink_manager/) | Zwraca menedżera hiperłącza.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides.smartart/smartart/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides.smartart/smartart/z_order_position/) | Zwraca pozycję kształtu w kolejności z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides.smartart/smartart/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides.smartart/smartart/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z.<br/>            Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides.smartart/smartart/x/) | Zwraca lub ustawia współrzędną x lewego górnego rogu kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides.smartart/smartart/y/) | Zwraca lub ustawia współrzędną y lewego górnego rogu kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides.smartart/smartart/width/) | Zwraca lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides.smartart/smartart/height/) | Zwraca lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides.smartart/smartart/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego..<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides.smartart/smartart/unique_id/) | Zwraca wewnętrzny identyfikator o zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować<br/>            jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides.smartart/smartart/office_interop_shape_id/) | Zwraca unikalny identyfikator o zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i<br/>            umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides.smartart/smartart/alternative_text/) | Zwraca lub ustawia alternatywny tekst powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides.smartart/smartart/alternative_text_title/) | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides.smartart/smartart/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides.smartart/smartart/is_decorative/) | Zwraca lub ustawia opcję 'Mark as decorative'<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides.smartart/smartart/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides.smartart/smartart/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides.smartart/smartart/parent_group/) | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides.smartart/smartart/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides.smartart/smartart/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides.smartart/smartart/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/pl/aspose.slides.smartart/smartart/all_nodes/) | Zwraca kolekcje wszystkich węzłów w obiekcie SmartArt.<br/>            Tylko do odczytu [`ISmartArtNodeCollection`](/slides/python-net/pl/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/pl/aspose.slides.smartart/smartart/nodes/) | Zwraca kolekcje węzłów głównych w obiekcie SmartArt.<br/>            Tylko do odczytu [`ISmartArtNodeCollection`](/slides/python-net/pl/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/pl/aspose.slides.smartart/smartart/layout/) | Zwraca lub ustawia układ obiektu SmartArt.<br/>            Odczyt/zapis [`SmartArtLayoutType`](/slides/python-net/pl/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/pl/aspose.slides.smartart/smartart/quick_style/) | Zwraca lub ustawia szybki styl obiektu SmartArt.<br/>            Odczyt/zapis [`SmartArtQuickStyleType`](/slides/python-net/pl/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/pl/aspose.slides.smartart/smartart/color_style/) | Zwraca lub ustawia styl kolorów obiektu SmartArt.<br/>            Odczyt/zapis [`SmartArtColorType`](/slides/python-net/pl/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/pl/aspose.slides.smartart/smartart/is_reversed/) | Zwraca lub ustawia stan diagramu SmartArt względem (od lewej do prawej) LTR lub (od prawej do lewej) RTL, jeśli diagram obsługuje odwrócenie.<br/>            Odczyt/zapis **bool**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides.smartart/smartart/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides.smartart/smartart/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides.smartart/smartart/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu master, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides.smartart/smartart/get_visual_bounds/#) | Zwraca wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`SmartArt`](/slides/python-net/pl/aspose.slides.smartart/smartart)
* moduł [`aspose.slides.smartart`](/slides/python-net/pl/aspose.slides.smartart)
* biblioteka [`Aspose.Slides`](/slides/python-net)