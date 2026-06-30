---
title: Chart
second_title: Aspose.Sildes dla .NET - Dokumentacja API
description: Reprezentuje graficzny wykres na slajdzie.
type: docs
weight: 1240
url: /pl/aspose.slides.charts/chart/
---
## Klasa Chart

Reprezentuje graficzny wykres na slajdzie.

```csharp
public class Chart : GraphicalObject, IChart
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt/zapis String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Umożliwia uzyskanie podstawowego interfejsu IFormattedTextContainer. Tylko do odczytu [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Umożliwia uzyskanie podstawowego interfejsu IThemeable. Tylko do odczytu [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Zapewnia dostęp do osi wykresu. Tylko do odczytu [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Zwraca obiekt, który umożliwia zmianę formatu tylnej ściany wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego.. Odczyt/zapis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Zwraca informacje o powiązanych lub osadzonych danych powiązanych z wykresem. Tylko do odczytu [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Zwraca tabelę danych wykresu. Tylko do odczytu [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Zwraca lub ustawia tytuł wykresu. Tylko do odczytu [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę punktów połączeń w kształcie. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca własne dane kształtu. Tylko do odczytu [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. Odczyt/zapis [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości efektu. Tylko do odczytu [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości wypełnienia. Tylko do odczytu [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Zwraca obiekt, który umożliwia zmianę formatu podłogi wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Określa, czy wykres posiada tabelę danych. Odczyt/zapis Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Określa, czy wykres posiada legendę. Odczyt/zapis Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Określa, że obszar wykresu ma mieć zaokrąglone narożniki. Odczyt/zapis Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Określa, czy wykres ma widoczny tytuł. Odczyt/zapis Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Pobiera lub ustawia wysokość kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżera hiperłączy. Tylko do odczytu [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszy. Odczyt/zapis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Pobiera lub ustawia opcję 'Mark as decorative'. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Zwraca lub ustawia legendę wykresu. Tylko do odczytu [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości linii. Tylko do odczytu [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Reprezentuje obszar rysowania wykresu. Tylko do odczytu [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Określa, czy rysowane są tylko widoczne komórki. False, aby rysować zarówno widoczne, jak i ukryte komórki. Odczyt/zapis Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o którą określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Odczyt/zapis Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Zwraca obrót 3D wykresu. Tylko do odczytu [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 właściwości) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. Odczyt/zapis Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Zwraca obiekt, który umożliwia zmianę formatu ściany bocznej wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca slajd nadrzędny kształtu. Tylko do odczytu [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Zwraca lub ustawia styl wykresu. Odczyt/zapis [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Zwraca format tekstu wykresu. Właściwość nie ma zastosowania do następujących typów: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Tylko do odczytu [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Zwraca menedżera motywu. Tylko do odczytu [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości 3D. Tylko do odczytu [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Zwraca lub ustawia typ wykresu. Odczyt/zapis [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy traktować jej jako trwałego unikalnego klucza. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Określa kształty rysowane na wierzchu wykresu. Tylko do odczytu [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Pobiera lub ustawia szerokość kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzona w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Zwraca efektywny motyw dla tego wykresu. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt). Zwraca null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę kształtu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiuje, że ten kształt nie jest placeholderem. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Oblicza rzeczywiste wartości elementów wykresu. Rzeczywiste wartości obejmują pozycje elementów implementujących interfejs IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) oraz rzeczywiste wartości osi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość Shape jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość Shape jako plik SVG. |

### Zobacz także

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->