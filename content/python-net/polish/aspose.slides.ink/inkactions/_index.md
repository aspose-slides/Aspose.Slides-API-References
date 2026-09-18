---
title: InkActions class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.ink/inkactions/
---
## InkActions klasa

Represents the root of ink actions.

**Inheritance:**[`InkActions`](/slides/python-net/pl/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

The InkActions type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides.ink/inkactions/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides.ink/inkactions/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides.ink/inkactions/custom_data/) | Zwraca dane niestandardowe kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides.ink/inkactions/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides.ink/inkactions/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides.ink/inkactions/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides.ink/inkactions/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides.ink/inkactions/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides.ink/inkactions/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides.ink/inkactions/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides.ink/inkactions/hyperlink_manager/) | Zwraca menedżer hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides.ink/inkactions/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides.ink/inkactions/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides.ink/inkactions/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides.ink/inkactions/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z.<br/>            Wartość dodatnia wskazuje obrót zgodny z ruchem wskazówek zegara; wartość ujemna wskazuje obrót przeciwny.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides.ink/inkactions/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides.ink/inkactions/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides.ink/inkactions/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides.ink/inkactions/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides.ink/inkactions/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego.<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides.ink/inkactions/unique_id/) | Zwraca wewnętrzny identyfikator powiązany z prezentacją, przeznaczony do użytku przez dodatki lub inny kod.<br/>            Ponieważ wartość tę można zmienić przez użytkownika lub programowo, nie należy traktować jej jako trwały unikalny klucz.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides.ink/inkactions/office_interop_shape_id/) | Zwraca unikalny identyfikator przypisany do slajdu, który pozostaje stały przez cały okres życia kształtu i umożliwia PowerPointowi lub kodowi interopowy niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides.ink/inkactions/alternative_text/) | Zwraca lub ustawia alternatywny tekst powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides.ink/inkactions/alternative_text_title/) | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides.ink/inkactions/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. Użyj pustego ciągu znaków w razie potrzeby.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides.ink/inkactions/is_decorative/) | Pobiera lub ustawia opcję „Mark as decorative”.<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides.ink/inkactions/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides.ink/inkactions/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides.ink/inkactions/parent_group/) | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides.ink/inkactions/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides.ink/inkactions/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides.ink/inkactions/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides.ink/inkactions/get_image/#) | Zwraca miniaturkę kształtu.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturkę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Zapisuje zawartość Shape jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość Shape jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides.ink/inkactions/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go brak, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides.ink/inkactions/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu master, z którego dziedziczony jest bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides.ink/inkactions/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |


### Zobacz także
* class [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* class [`InkActions`](/slides/python-net/pl/aspose.slides.ink/inkactions)
* class [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* module [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)