---
title: Ink class
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides.ink/ink/
---
## Klasa Ink

Reprezentuje obiekt atramentu na slajdzie.

**Inheritance:**[`Ink`](/slides/python-net/pl/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ Ink udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides.ink/ink/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides.ink/ink/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholder.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides.ink/ink/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides.ink/ink/raw_frame/) | Pobiera lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides.ink/ink/frame/) | Pobiera lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides.ink/ink/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides.ink/ink/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides.ink/ink/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides.ink/ink/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides.ink/ink/hyperlink_click/) | Pobiera lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides.ink/ink/hyperlink_mouse_over/) | Pobiera lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides.ink/ink/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides.ink/ink/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides.ink/ink/z_order_position/) | Zwraca pozycję kształtu w kolejności z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides.ink/ink/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides.ink/ink/rotation/) | Pobiera lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z.<br/>            Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides.ink/ink/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides.ink/ink/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides.ink/ink/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides.ink/ink/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides.ink/ink/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białym.<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides.ink/ink/unique_id/) | Zwraca wewnętrzny identyfikator zakresu prezentacji przeznaczony do użytku przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować<br/>            jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides.ink/ink/office_interop_shape_id/) | Zwraca unikalny identyfikator zakresu slajdu, który pozostaje stały przez cały okres życia kształtu i<br/>            pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides.ink/ink/alternative_text/) | Pobiera lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides.ink/ink/alternative_text_title/) | Pobiera lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides.ink/ink/name/) | Pobiera lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides.ink/ink/is_decorative/) | Pobiera lub ustawia opcję „Oznacz jako dekoracyjny”.<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides.ink/ink/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides.ink/ink/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides.ink/ink/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides.ink/ink/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides.ink/ink/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides.ink/ink/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/pl/aspose.slides.ink/ink/traces/) | Pobiera wszystkie ślady zawarte w elemencie IInk [`IInkTrace`](/slides/python-net/pl/aspose.slides.ink/iinktrace).<br/>            Tylko do odczytu. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides.ink/ink/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape definiujący granice miniatury. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides.ink/ink/remove_placeholder/#) | Określa, że ten kształt nie jest placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides.ink/ink/get_base_placeholder/#) | Zwraca podstawowy placeholder shape (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides.ink/ink/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/pl/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Rejestruje obraz w kolekcji niestandardowych obrazów używanych do symulacji efektów wizualnych pędzli atramentu.<br/>            Obrazy te są używane przy renderowaniu atramentu z konkretnymi wartościami [`InkEffectType`](/slides/python-net/pl/aspose.slides.ink/inkeffecttype),<br/>            takimi jak Galaxy, Rainbow itp. Dostarczając własne obrazy, możesz kontrolować, jak każdy efekt atramentu się wyświetla. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/pl/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Wyrejestrowuje obraz z kolekcji niestandardowych obrazów używanych do symulacji efektów wizualnych pędzli atramentu<br/>            wcześniej zarejestrowanych obrazów za pomocą **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Ink`](/slides/python-net/pl/aspose.slides.ink/ink)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* biblioteka [`Aspose.Slides`](/slides/python-net)