---
title: Chart class
second_title: Aspose.Slides dla Pythona poprzez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/chart/
---
## Chart klasa

Reprezentuje graficzny wykres na slajdzie.

**Dziedziczenie:**[`Chart`](/slides/python-net/pl/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

Typ Chart udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides.charts/chart/is_text_holder/) | Określa, czy kształt jest TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides.charts/chart/placeholder/) | Zwraca placeholder dla kształtu. Zwraca None, jeśli kształt nie ma placeholdera.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides.charts/chart/custom_data/) | Zwraca dane niestandardowe kształtu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides.charts/chart/raw_frame/) | Zwraca lub ustawia właściwości surowej ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides.charts/chart/frame/) | Zwraca lub ustawia właściwości ramki kształtu.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides.charts/chart/line_format/) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości linii.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides.charts/chart/three_d_format/) | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości 3D.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides.charts/chart/effect_format/) | Zwraca obiekt EffectFormat zawierający efekty pikselowe stosowane do kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości efektów.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides.charts/chart/fill_format/) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu.<br/>            Uwaga: może zwrócić None dla niektórych typów kształtów, które nie mają właściwości wypełnienia.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides.charts/chart/hyperlink_click/) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides.charts/chart/hyperlink_mouse_over/) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides.charts/chart/hyperlink_manager/) | Zwraca menedżer hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides.charts/chart/hidden/) | Określa, czy kształt jest ukryty.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides.charts/chart/z_order_position/) | Zwraca pozycję kształtu w kolejności Z.<br/>            Shapes[0] zwraca kształt znajdujący się na końcu kolejności Z,<br/>            a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się na początku kolejności Z.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides.charts/chart/connection_site_count/) | Zwraca liczbę punktów połączeń na kształcie.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides.charts/chart/rotation/) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół<br/>            osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna<br/>            oznacza obrót przeciwny do ruchu wskazówek zegara.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides.charts/chart/x/) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides.charts/chart/y/) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides.charts/chart/width/) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides.charts/chart/height/) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides.charts/chart/black_white_mode/) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białym..<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides.charts/chart/unique_id/) | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użytku przez dodatki lub inny kod.<br/>            Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy traktować jej jako trwałego unikalnego klucza.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides.charts/chart/office_interop_shape_id/) | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i<br/>            umożliwia programowi PowerPoint lub kodowi interop bezpieczne odwoływanie się do kształtu z dowolnego miejsca dokumentu.<br/>            Tylko do odczytu **int**.<br/>            Zobacz także [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides.charts/chart/alternative_text/) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides.charts/chart/alternative_text_title/) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides.charts/chart/name/) | Zwraca lub ustawia nazwę kształtu.<br/>            Musi nie być None. Użyj pustego ciągu znaków w razie potrzeby.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides.charts/chart/is_decorative/) | Pobiera lub ustawia opcję 'Mark as decorative'<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides.charts/chart/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides.charts/chart/is_grouped/) | Określa, czy kształt jest grupowany.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides.charts/chart/parent_group/) | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/chart/slide/) | Zwraca slajd nadrzędny kształtu.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/chart/presentation/) | Zwraca prezentację nadrzędną slajdu.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides.charts/chart/graphical_object_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/pl/aspose.slides.charts/chart/plot_visible_cells_only/) | Określa, czy wykreślane są tylko widoczne komórki. False, aby wykreślić zarówno widoczne, jak i ukryte komórki.<br/>            Odczyt/zapis **bool**. |
| [`display_blanks_as`](/slides/python-net/pl/aspose.slides.charts/chart/display_blanks_as/) | Zwraca lub ustawia sposób wykreślania pustych komórek na wykresie.<br/>            Odczyt/zapis [`DisplayBlanksAsType`](/slides/python-net/pl/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/pl/aspose.slides.charts/chart/chart_data/) | Zwraca informacje o powiązanych lub osadzonych danych powiązanych z wykresem.<br/>            Tylko do odczytu [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/pl/aspose.slides.charts/chart/has_title/) | Określa, czy wykres ma widoczny tytuł.<br/>            Odczyt/zapis **bool**. |
| [`chart_title`](/slides/python-net/pl/aspose.slides.charts/chart/chart_title/) | Zwraca lub ustawia tytuł wykresu.<br/>            Tylko do odczytu [`IChartTitle`](/slides/python-net/pl/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/pl/aspose.slides.charts/chart/has_data_table/) | Określa, czy wykres ma tabelę danych.<br/>            Odczyt/zapis **bool**. |
| [`has_legend`](/slides/python-net/pl/aspose.slides.charts/chart/has_legend/) | Określa, czy wykres ma legendę.<br/>            Odczyt/zapis **bool**. |
| [`legend`](/slides/python-net/pl/aspose.slides.charts/chart/legend/) | Zwraca lub ustawia legendę wykresu.<br/>            Tylko do odczytu [`ILegend`](/slides/python-net/pl/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/pl/aspose.slides.charts/chart/chart_data_table/) | Zwraca tabelę danych wykresu.<br/>            Tylko do odczytu [`IDataTable`](/slides/python-net/pl/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/pl/aspose.slides.charts/chart/style/) | Zwraca lub ustawia styl wykresu.<br/>            Odczyt/zapis [`StyleType`](/slides/python-net/pl/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/pl/aspose.slides.charts/chart/type/) | Zwraca lub ustawia typ wykresu.<br/>            Odczyt/zapis [`ChartType`](/slides/python-net/pl/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/pl/aspose.slides.charts/chart/plot_area/) | Reprezentuje obszar kreślenia wykresu.<br/>            Tylko do odczytu [`IChartPlotArea`](/slides/python-net/pl/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/pl/aspose.slides.charts/chart/rotation_3d/) | Zwraca obrót 3D wykresu.<br/>            Tylko do odczytu [`IRotation3D`](/slides/python-net/pl/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/pl/aspose.slides.charts/chart/back_wall/) | Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D.<br/>            Tylko do odczytu [`IChartWall`](/slides/python-net/pl/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/pl/aspose.slides.charts/chart/side_wall/) | Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D.<br/>            Tylko do odczytu [`IChartWall`](/slides/python-net/pl/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/pl/aspose.slides.charts/chart/floor/) | Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D.<br/>            Tylko do odczytu [`IChartWall`](/slides/python-net/pl/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/pl/aspose.slides.charts/chart/text_format/) | Zwraca format tekstu wykresu.<br/>            Właściwość nie ma zastosowania dla następujących typów: [`ChartType.TREEMAP`](/slides/python-net/pl/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/pl/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/pl/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/pl/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/pl/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/pl/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Tylko do odczytu [`IChartTextFormat`](/slides/python-net/pl/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/pl/aspose.slides.charts/chart/theme_manager/) | Zwraca menedżer motywu.<br/>            Tylko do odczytu [`IOverrideThemeManager`](/slides/python-net/pl/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/pl/aspose.slides.charts/chart/user_shapes/) | Określ kształty rysowane na wierzchu wykresu.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/pl/aspose.slides.charts/chart/axes/) | Zapewnia dostęp do osi wykresu.<br/>            Tylko do odczytu [`IAxesManager`](/slides/python-net/pl/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/pl/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Określa, czy etykiety danych powyżej maksymalnej wartości wykresu mają być wyświetlane.<br/>            Odczyt/zapis **bool**. |
| [`has_rounded_corners`](/slides/python-net/pl/aspose.slides.charts/chart/has_rounded_corners/) | Określa, że obszar wykresu ma mieć zaokrąglone narożniki.<br/>            Odczyt/zapis **bool**. |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/chart/chart/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides.charts/chart/get_image/#) | Zwraca miniaturkę kształtu.<br/>            Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniaturki kształtu. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Zwraca miniaturkę kształtu. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Zapisuje zawartość kształtu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość kształtu jako plik SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides.charts/chart/remove_placeholder/#) | Definiuje, że ten kształt nie jest placeholderem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides.charts/chart/get_base_placeholder/#) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu-matki, z którego dziedziczy bieżący kształt).<br/>            Zwraca None, jeśli bieżący kształt nie jest dziedziczony. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides.charts/chart/get_visual_bounds/#) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [`validate_chart_layout(self)`](/slides/python-net/pl/aspose.slides.charts/chart/validate_chart_layout/#) | Oblicza rzeczywiste wartości elementów wykresu. Rzeczywiste wartości obejmują pozycję elementów implementujących interfejs IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            oraz rzeczywiste wartości osi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides.charts/chart/create_theme_effective/#) | Zwraca efektywny motyw dla tego wykresu. |

### Zobacz także
* klasa [`Chart`](/slides/python-net/pl/aspose.slides.charts/chart)
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)