---
title: LegacyDiagram class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/legacydiagram/
---
## Klasa LegacyDiagram

Reprezentuje obiekt klasycznego diagramu.

**Dziedziczenie:**[`LegacyDiagram`](/slides/python-net/pl/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ LegacyDiagram udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/legacydiagram/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko odczyt **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/legacydiagram/placeholder/) | Zwraca element zastępczy dla kształtu. Zwraca None, jeśli kształt nie ma elementu zastępczego.<br/>            Tylko odczyt [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/legacydiagram/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko odczyt [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/legacydiagram/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/legacydiagram/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/legacydiagram/line_format/) | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko odczyt [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/legacydiagram/three_d_format/) | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko odczyt [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/legacydiagram/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikseli zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko odczyt [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/legacydiagram/fill_format/) | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko odczyt [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/legacydiagram/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/legacydiagram/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko odczyt [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/legacydiagram/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/legacydiagram/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z.<br/>            Tylko odczyt **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/legacydiagram/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            Tylko odczyt **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/legacydiagram/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z.<br/>            Pozytywna wartość wskazuje obrót w prawo (zgodnie z ruchem wskazówek zegara); negatywna wartość wskazuje obrót w lewo (przeciwnie do ruchu wskazówek zegara).<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/legacydiagram/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/legacydiagram/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/legacydiagram/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/legacydiagram/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/legacydiagram/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym.<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/legacydiagram/unique_id/) | Zwraca wewnętrzny identyfikator scoped do prezentacji, przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz.<br/>            Tylko odczyt **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/legacydiagram/office_interop_shape_id/) | Zwraca unikalny identyfikator scoped do slajdu, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interop na niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko odczyt **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/legacydiagram/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/legacydiagram/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/legacydiagram/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Musi nie być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/legacydiagram/is_decorative/) | Pobiera lub ustawia opcję 'Oznacz jako dekoracyjne'<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/legacydiagram/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko odczyt [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/legacydiagram/is_grouped/) | Określa, czy kształt jest zgrupowany.<br/>            Tylko odczyt **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/legacydiagram/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest zgrupowany. W przeciwnym razie zwraca None.<br/>            Tylko odczyt [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/legacydiagram/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko odczyt [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/legacydiagram/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko odczyt [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/legacydiagram/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko odczyt [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/legacydiagram/get_image/#) | Zwraca miniaturkę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniaturki kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturkę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/legacydiagram/remove_placeholder/#) | Określa, że ten kształt nie jest elementem zastępczym. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Dodaje nowy element zastępczy, jeśli go nie ma, i ustawia właściwości elementu zastępczego na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/legacydiagram/get_base_placeholder/#) | Zwraca podstawowy kształt elementu zastępczego (kształt z układu i/lub slajdu nadrzędnego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/legacydiagram/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`convert_to_smart_art(self)`](/slides/python-net/pl/aspose.slides/legacydiagram/convert_to_smart_art/#) | Konwertuje starszy diagram na edytowalny obiekt SmartArt. <br/>            Utworzony obiekt SmartArt jest dodawany do nadrzędnego GroupShape w tej samej pozycji. |
| [`convert_to_group_shape(self)`](/slides/python-net/pl/aspose.slides/legacydiagram/convert_to_group_shape/#) | Konwertuje starszy diagram na edytowalny grupowy kształt. <br/>            Utworzony obiekt GroupShape jest dodawany do nadrzędnego GroupShape w tej samej pozycji. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`LegacyDiagram`](/slides/python-net/pl/aspose.slides/legacydiagram)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)