---
title: OleObjectFrame class
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/oleobjectframe/
---
## OleObjectFrame klasa

Reprezentuje obiekt OLE na slajdzie.

**Dziedziczenie:**[`OleObjectFrame`](/slides/python-net/pl/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ OleObjectFrame udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/oleobjectframe/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/oleobjectframe/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/oleobjectframe/custom_data/) | Zwraca dane niestandardowe kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/oleobjectframe/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/oleobjectframe/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/oleobjectframe/line_format/) | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/oleobjectframe/three_d_format/) | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/oleobjectframe/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/oleobjectframe/fill_format/) | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/oleobjectframe/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/oleobjectframe/hyperlink_manager/) | Zwraca menedżera hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/oleobjectframe/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/oleobjectframe/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/oleobjectframe/connection_site_count/) | Zwraca liczbę punktów połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/oleobjectframe/rotation/) | Zwraca lub ustawia liczbę stopni, o które zadany kształt jest obrócony wokół osi Z.<br/>            Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/oleobjectframe/x/) | Zwraca lub ustawia współrzędną X lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/oleobjectframe/y/) | Zwraca lub ustawia współrzędną Y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/oleobjectframe/width/) | Zwraca lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/oleobjectframe/height/) | Zwraca lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/oleobjectframe/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego..<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/oleobjectframe/unique_id/) | Zwraca wewnętrzny identyfikator o zakresie prezentacji przeznaczony do użytku przez dodatki lub inny kod.<br/>            Ponieważ wartość tę można ponownie przypisać przez użytkownika lub programowo, nie należy jej traktować<br/>            jako trwały unikalny klucz.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/oleobjectframe/office_interop_shape_id/) | Zwraca unikalny identyfikator o zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i<br/>            umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/oleobjectframe/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/oleobjectframe/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/oleobjectframe/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Nie może być None. W razie potrzeby użyj pustego łańcucha.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/oleobjectframe/is_decorative/) | Zwraca lub ustawia opcję „Oznacz jako dekoracyjne”.<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/oleobjectframe/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/oleobjectframe/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/oleobjectframe/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/oleobjectframe/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/oleobjectframe/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/oleobjectframe/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/pl/aspose.slides/oleobjectframe/substitute_picture_format/) | Zwraca obiekt właściwości wypełniania obrazu OleObject.<br/>            Tylko do odczytu [`IPictureFillFormat`](/slides/python-net/pl/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/pl/aspose.slides/oleobjectframe/substitute_picture_title/) | Zwraca lub ustawia tytuł ikony OleObject.<br/>            Odczyt/zapis **str**. |
| [`object_name`](/slides/python-net/pl/aspose.slides/oleobjectframe/object_name/) | Zwraca lub ustawia nazwę obiektu.<br/>            Odczyt/zapis **str**. |
| [`object_prog_id`](/slides/python-net/pl/aspose.slides/oleobjectframe/object_prog_id/) | Zwraca ProgID obiektu.<br/>            Tylko do odczytu **str**. |
| [`link_file_name`](/slides/python-net/pl/aspose.slides/oleobjectframe/link_file_name/) | Zwraca pełną ścieżkę do połączonego pliku. Używana będzie krótka nazwa pliku.<br/>            Tylko do odczytu **str**. |
| [`link_path_long`](/slides/python-net/pl/aspose.slides/oleobjectframe/link_path_long/) | Zwraca pełną ścieżkę do połączonego pliku. Używana będzie długa nazwa pliku.<br/>            Odczyt/zapis **str**. |
| [`link_path_relative`](/slides/python-net/pl/aspose.slides/oleobjectframe/link_path_relative/) | Zwraca względną ścieżkę do połączonego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty łańcuch.<br/>             Tylko do odczytu **str**. |
| [`embedded_file_label`](/slides/python-net/pl/aspose.slides/oleobjectframe/embedded_file_label/) | Zwraca nazwę pliku osadzonego obiektu OLE |
| [`embedded_file_name`](/slides/python-net/pl/aspose.slides/oleobjectframe/embedded_file_name/) | Zwraca ścieżkę osadzonego obiektu OLE |
| [`embedded_data`](/slides/python-net/pl/aspose.slides/oleobjectframe/embedded_data/) | Zwraca lub ustawia informacje o osadzonych danych OLE.<br/>            Odczyt/zapis [`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/pl/aspose.slides/oleobjectframe/is_object_icon/) | Określa, czy obiekt jest widoczny jako ikona.<br/>            Odczyt/zapis **bool**. |
| [`is_object_link`](/slides/python-net/pl/aspose.slides/oleobjectframe/is_object_link/) | Określa, czy obiekt jest połączony z zewnętrznym plikiem.<br/>            Tylko do odczytu **bool**. |
| [`update_automatic`](/slides/python-net/pl/aspose.slides/oleobjectframe/update_automatic/) | Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany przy otwieraniu lub drukowaniu prezentacji.<br/>            Odczyt/zapis **bool**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/oleobjectframe/get_image/#) | Zwraca miniaturkę kształtu.<br/>            Typ ShapeThumbnailBounds.Shape jest używany domyślnie dla granic miniaturki kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturkę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/oleobjectframe/remove_placeholder/#) | Określa, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go brak, i ustawia jego właściwości na określone. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/oleobjectframe/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/oleobjectframe/get_visual_bounds/#) | Zwraca wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/pl/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Ustawia informacje o osadzonych danych OLE.<br/>            <br/>            Ta metoda zmienia właściwości obiektu, aby odzwierciedlały nowe dane i <br/>            ustawia flagę IsObjectLink na false, co wskazuje, że obiekt OLE jest osadzony. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`OleObjectFrame`](/slides/python-net/pl/aspose.slides/oleobjectframe)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)