---
title: Chart
second_title: Aspose.Slides dla C++ – Referencja API
description: Reprezentuje wykres graficzny na slajdzie.
type: docs
weight: 53
url: /pl/aspose.slides.charts/chart/
---
## Chart klasa

Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Dodaje nowy element zastępczy, jeśli go nie ma, i ustawia właściwości elementu zastępczego na określony. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | Zwraca efektywny temat dla tego wykresu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Zwraca tekst alternatywny powiązany z kształtem. Zobacz [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Zobacz [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | Zapewnia dostęp do osi wykresu. Tylko do odczytu [IAxesManager](../iaxesmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D. Tylko do odczytu [IChartWall](../ichartwall/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zobacz [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | Zwraca informacje o powiązanych lub osadzonych danych powiązanych z wykresem. Tylko do odczytu [IChartData](../ichartdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | Zwraca tabelę danych wykresu. Tylko do odczytu [IDataTable](../idatatable/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | Zwraca tytuł wykresu. Tylko do odczytu [IChartTitle](../icharttitle/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../../aspose.slides/icustomdata/). |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | Zwraca sposób rysowania pustych komórek na wykresie. Zobacz [DisplayBlanksAsType](../displayblanksastype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Zwraca obiekt [EffectFormat](../../aspose.slides/effectformat/), który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości efektów. Tylko do odczytu [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Zwraca obiekt [FillFormat](../../aspose.slides/fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości wypełnienia. Tylko do odczytu [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D. Tylko do odczytu [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Zwraca właściwości ramki kształtu. Zobacz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | Określa, czy wykres posiada tabelę danych. Zobacz **bool**. |
| **bool** [get_HasLegend](./get_haslegend/)() override | Określa, czy wykres posiada legendę. Zobacz **bool**. |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | Określa, że obszar wykresu ma mieć zaokrąglone rogi. Zobacz **bool**. |
| **bool** [get_HasTitle](./get_hastitle/)() override | Określa, czy wykres ma widoczny tytuł. Zobacz **bool**. |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Pobiera wysokość kształtu, mierzoną w punktach. Zobacz **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Określa, czy kształt jest ukryty. Zobacz **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Zwraca hiperlink zdefiniowany dla kliknięcia myszy. Zobacz [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Zwraca menedżera hiperlinków. Tylko do odczytu [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Zwraca hiperlink zdefiniowany dla najechania myszą. Zobacz [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Pobiera opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Określa, czy kształt jest grupowany. Tylko do odczytu **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | Zwraca legendę wykresu. Tylko do odczytu [ILegend](../ilegend/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Zwraca obiekt [LineFormat](../../aspose.slides/lineformat/), który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości linii. Tylko do odczytu [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Zwraca nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu znaków. Zobacz [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Zwraca obiekt nadrzędny [GroupShape](../../aspose.slides/groupshape/), jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Zwraca element zastępczy dla kształtu. Zwraca null, jeśli kształt nie ma elementu zastępczego. Tylko do odczytu [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | Reprezentuje obszar rysowania wykresu. Tylko do odczytu [IChartPlotArea](../ichartplotarea/). |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | Określa, czy rysowane są tylko widoczne komórki. False, aby rysować zarówno widoczne, jak i ukryte komórki. Zobacz **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Zwraca surowe właściwości ramki kształtu. Zobacz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Zwraca liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – przeciwny. Zobacz **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | Zwraca obrót 3D wykresu. Tylko do odczytu [IRotation3D](../irotation3d/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. Zobacz **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D. Tylko do odczytu [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Zwraca slajd nadrzędny kształtu. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | Zwraca styl wykresu. Zobacz [StyleType](../styletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Zwraca format tekstu wykresu. Właściwość nie ma zastosowania dla następujących typów: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/). Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Zwraca menedżera tematów. Tylko do odczytu [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../../aspose.slides/threedformat/) zawierający właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko do odczytu [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | Zwraca typ wykresu. Zobacz [ChartType](../charttype/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy traktować jej jako trwały unikalny klucz. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | Określa kształty rysowane na wierzchu wykresu. Tylko do odczytu [IGroupShape](../../aspose.slides/igroupshape/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Pobiera szerokość kształtu, mierzoną w punktach. Zobacz **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Pobiera współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zobacz **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Pobiera współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zobacz **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Zwraca miniaturę kształtu. Domyślnie używany jest typ granic miniatury [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Zwraca miniaturę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Definiuje, że ten kształt nie jest elementem zastępczym. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Ustawia tekst alternatywny powiązany z kształtem. Zapis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapis [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zapis [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | Ustawia sposób rysowania pustych komórek na wykresie. Zapis [DisplayBlanksAsType](../displayblanksastype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ustawia właściwości ramki kształtu. Zapis [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | Określa, czy wykres posiada tabelę danych. Zapis **bool**. |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | Określa, czy wykres posiada legendę. Zapis **bool**. |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | Określa, że obszar wykresu ma mieć zaokrąglone rogi. Zapis **bool**. |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Określa, czy wykres ma widoczny tytuł. Zapis **bool**. |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Ustawia wysokość kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Określa, czy kształt jest ukryty. Zapis **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Ustawia hiperlink zdefiniowany dla kliknięcia myszy. Zapis [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Ustawia hiperlink zdefiniowany dla najechania myszą. Zapis [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Ustawia opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu znaków. Zapis [System::String](../../system/string/). |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | Określa, czy rysowane są tylko widoczne komórki. False, aby rysować zarówno widoczne, jak i ukryte komórki. Zapis **bool**. |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ustawia surowe właściwości ramki kształtu. Zapis [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – przeciwny. Zapis **float**. |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. Zapis **bool**. |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | Ustawia styl wykresu. Zapis [StyleType](../styletype/). |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | Ustawia typ wykresu. Zapis [ChartType](../charttype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Ustawia szerokość kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| void [ValidateChartLayout](./validatechartlayout/)() override | Oblicza rzeczywiste wartości elementów wykresu. Rzeczywiste wartości obejmują pozycję elementów implementujących interfejs [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) oraz rzeczywiste wartości osi ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Zapisuje zawartość [Shape](../../aspose.slides/shape/) jako plik SVG. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Zapisuje zawartość [Shape](../../aspose.slides/shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [GraphicalObject](../../aspose.slides/graphicalobject/)
* Klasa [IChart](../ichart/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)