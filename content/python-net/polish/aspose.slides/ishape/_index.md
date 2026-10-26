---
title: IShape class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ishape/
---
## IShape klasa

Represents a shape on a slide.

The IShape type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/ishape/is_text_holder/) | Określa, czy kształt jest TextHolder.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/ishape/placeholder/) | Zwraca zastępczy element dla kształtu.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/ishape/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/ishape/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/ishape/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/ishape/line_format/) | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/ishape/three_d_format/) | Zwraca obiekt ThreeDFormat, który zawiera właściwości formatowania linii dla kształtu.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/ishape/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/ishape/fill_format/) | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/pl/aspose.slides/ishape/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/ishape/z_order_position/) | Zwraca pozycję kształtu w kolejności z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/ishape/connection_site_count/) | Zwraca liczbę punktów połączenia na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/ishape/rotation/) | Zwraca lub ustawia liczbę stopni, o którą określony kształt jest obrócony wokół osi z.<br/>            Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/ishape/x/) | Pobiera lub ustawia współrzędną x lewego górnego narożnika kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/ishape/y/) | Pobiera lub ustawia współrzędną y lewego górnego narożnika kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/ishape/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/ishape/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/ishape/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/ishape/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/ishape/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/ishape/is_decorative/) | Pobiera lub ustawia opcję 'Mark as decorative'<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/ishape/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IBaseShapeLock`](/slides/python-net/pl/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/ishape/unique_id/) | Zwraca wewnętrzny identyfikator o zakresie prezentacji, przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość tę można ponownie przypisać przez użytkownika lub programowo, nie należy traktować<br/>            jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`IShape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/ishape/office_interop_shape_id/) | Zwraca unikalny identyfikator o zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i<br/>            pozwala PowerPointowi lub kodowi interop odwoływać się do kształtu w dowolnym miejscu dokumentu.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`IShape.unique_id`](/slides/python-net/pl/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/ishape/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/ishape/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego.<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/pl/aspose.slides/ishape/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/ishape/hyperlink_manager/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/ishape/get_image/#) | Zwraca miniaturę kształtu.<br/>            Typ ShapeThumbnailBounds.Shape jest domyślnie używany do określenia granic miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/ishape/write_as_svg/#iorawiobase) | Zapisuje zawartość Shape jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość Shape jako plik SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/ishape/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/ishape/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/ishape/get_base_placeholder/#) | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu nadrzędnego, z którego dziedziczony jest bieżący kształt).<br/>            Zwracane jest None, jeśli bieżący kształt nie jest dziedziczony. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)