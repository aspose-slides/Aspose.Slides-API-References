---
title: PictureFrame class
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/pictureframe/
---
## PictureFrame klasa

Reprezentuje ramkę z obrazem w środku.

**Dziedziczenie:**[`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ PictureFrame udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/pictureframe/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/pictureframe/placeholder/) | Zwraca zastępnik dla kształtu. Zwraca None, jeśli kształt nie ma zastępnika.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/pictureframe/custom_data/) | Zwraca niestandardowe dane kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/pictureframe/raw_frame/) | Zwraca lub ustawia surowe właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/pictureframe/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/pictureframe/line_format/) | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/pictureframe/three_d_format/) | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektu 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/pictureframe/effect_format/) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektu.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/pictureframe/fill_format/) | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/pictureframe/hyperlink_click/) | Zwraca lub ustawia hiperłącze definiowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/pictureframe/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze definiowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/pictureframe/hyperlink_manager/) | Zwraca menedżer hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/pictureframe/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/pictureframe/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt na końcu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt na początku kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/pictureframe/connection_site_count/) | Zwraca liczbę miejsc połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/pictureframe/rotation/) | Zwraca lub ustawia liczbę stopni, o które podany kształt jest obrócony wokół osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwnie do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/pictureframe/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/pictureframe/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/pictureframe/width/) | Pobiera lub ustawia szerokość kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/pictureframe/height/) | Pobiera lub ustawia wysokość kształtu, mierzona w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/pictureframe/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego.<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/pictureframe/unique_id/) | Zwraca wewnętrzny identyfikator o zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy traktować jej jako trwałego unikatowego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/pictureframe/office_interop_shape_id/) | Zwraca unikatowy identyfikator o zakresie slajdu, który pozostaje stały przez cały okres życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/pictureframe/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/pictureframe/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/pictureframe/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Musi nie być None. W razie potrzeby użyj pustego ciągu znaków.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/pictureframe/is_decorative/) | Pobiera lub ustawia opcję 'Oznacz jako dekoracyjny'<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/pictureframe/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IPictureFrameLock`](/slides/python-net/pl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/pictureframe/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/pictureframe/parent_group/) | Zwraca obiekt rodzica GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/pictureframe/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/pictureframe/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pl/aspose.slides/pictureframe/shape_style/) | Zwraca obiekt stylu kształtu.<br/>            Tylko do odczytu [`IShapeStyle`](/slides/python-net/pl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pl/aspose.slides/pictureframe/shape_type/) | Zwraca lub ustawia typ AutoShape dla PictureFrame.<br/>            Dozwolone są wszystkie elementy zbioru [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype), <br/>            z wyjątkiem wszystkich rodzajów linii:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Odczyt/zapis [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pl/aspose.slides/pictureframe/adjustments/) | Zwraca kolekcję wartości regulacji kształtu.<br/>            Tylko do odczytu [`IAdjustValueCollection`](/slides/python-net/pl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/pl/aspose.slides/pictureframe/picture_frame_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IPictureFrameLock`](/slides/python-net/pl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/pl/aspose.slides/pictureframe/picture_format/) | Zwraca obiekt PictureFillFormat dla ramki obrazu.<br/>            Tylko do odczytu [`IPictureFillFormat`](/slides/python-net/pl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/pl/aspose.slides/pictureframe/relative_scale_height/) | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%.<br/>            Odczyt/zapis **float**. |
| [`relative_scale_width`](/slides/python-net/pl/aspose.slides/pictureframe/relative_scale_width/) | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%.<br/>            Odczyt/zapis **float**. |
| [`is_cameo`](/slides/python-net/pl/aspose.slides/pictureframe/is_cameo/) | Określa, czy PictureFrame jest obiektem Cameo, czy nie.<br/>            Tylko do odczytu **bool**. |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/pictureframe/get_image/#) | Zwraca miniaturę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniatury kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/pictureframe/remove_placeholder/#) | Określa, że ten kształt nie jest zastępcą. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Dodaje nowy zastępnik, jeśli nie ma, i ustawia właściwości zastępnika na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/pictureframe/get_base_placeholder/#) | Zwraca podstawowy kształt zastępnika (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/pictureframe/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/pictureframe/get_geometry_paths/#) | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względem lewego górnego rogu kształtu. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu.<br/>            Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu.<br/>            Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/pictureframe/create_shape_elements/#) | Tworzy i zwraca tablicę elementów kształtu. |

### Zobacz również
* klasa [`GeometryShape`](/slides/python-net/pl/aspose.slides/geometryshape)
* klasa [`PictureFrame`](/slides/python-net/pl/aspose.slides/pictureframe)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)