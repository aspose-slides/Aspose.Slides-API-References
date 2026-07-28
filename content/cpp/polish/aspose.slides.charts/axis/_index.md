---
title: Axis
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Enkapsuluje obiekt, który reprezentuje oś wykresu.
type: docs
weight: 14
url: /pl/aspose.slides.charts/axis/
---
## Axis klasa

Enkapsuluje obiekt, który reprezentuje oś wykresu.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Określa rzeczywistą jednostkę główną osi. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywistą wartość. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Określa rzeczywistą skalę jednostki głównej osi. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywistą wartość. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Określa rzeczywistą maksymalną wartość na osi. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywistą wartość. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Określa rzeczywistą jednostkę podrzędną osi. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywistą wartość. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Określa rzeczywistą skalę jednostki podrzędnej osi. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywistą wartość. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Określa rzeczywistą minimalną wartość na osi. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywistą wartość. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Reprezentuje typ agregacji osi kategorii (grupowanie). Zastosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość ma zastosowanie tylko do osi kategorii i nie dotyczy wykresów 3-D. Odczyt **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Określa szerokość przedziału, gdy wartość właściwości AggregationType jest ustawiona na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Zastosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Określa typ osi kategorii. Odczyt [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Reprezentuje punkt na osi, w którym oś prostopadła ją przecina. Odczyt **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Reprezentuje CrossType na określonej osi, w której inna oś ją przecina. Odczyt [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Odczyt [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Reprezentuje format osi. Tylko do odczytu [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Określa, czy oś ma widoczny tytuł. Odczyt **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Odczyt **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Odczyt **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. Odczyt **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Odczyt **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Określa automatyczną wartość przedziału przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Określa automatyczną wartość odstępu etykiet podziałki. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Określa automatyczną wartość odstępu znaczników podziałki. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Określa automatyczną wartość przedziału podprzepełnienia. Jeśli false: użyj właściwości UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Odczyt **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Wskazuje, czy format jest połączony z danymi źródłowymi. Odczyt **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Określa, czy zastosowano przedział przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość przedziału przepełnienia. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Reprezentuje, czy MS PowerPoint rysuje punkty danych od końca do początku. Odczyt **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Określa, czy zastosowano przedział podprzepełnienia. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość przedziału podprzepełnienia. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Reprezentuje, czy oś jest widoczna. Odczyt **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Określa odległość etykiet od osi. Zastosowane do osi kategorii lub daty. Wartość musi być pomiędzy 0 % a 1000 %. Odczyt **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Reprezentuje format głównych linii siatki na osi wykresu. Tylko do odczytu [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Reprezentuje typ głównego znacznika podziałki dla określonej osi. Odczyt [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Reprezentuje skalę jednostki głównej dla osi daty. Odczyt [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Reprezentuje maksymalną wartość na osi wartości. Odczyt **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Reprezentuje format mniejszych linii siatki na osi wykresu. Tylko do odczytu [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Reprezentuje typ mniejszego znacznika podziałki dla określonej osi. Odczyt [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Reprezentuje jednostki mniejsze dla osi daty lub wartości. Odczyt **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Reprezentuje skalę jednostki głównej dla osi daty. Odczyt [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Reprezentuje minimalną wartość na osi wartości. Odczyt **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Reprezentuje ciąg formatu dla etykiet [Axis](./). Odczyt [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Określa liczbę przedziałów, gdy wartość właściwości AggregationType jest ustawiona na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Zastosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Określa niestandardową wartość przedziału przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i IsOverflowBin równa się true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Reprezentuje pozycję osi. Odczyt [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Aby ukryć główną linię siatki, ustaw [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() na [FillType::NoFill](../../aspose.slides/filltype/). Tylko do odczytu **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Aby ukryć mniejszą linię siatki, ustaw [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() na [FillType::NoFill](../../aspose.slides/filltype/). Tylko do odczytu **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Reprezentuje format tekstu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Reprezentuje pozycję etykiet znaczników podziałki na określonej osi. Odczyt [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Reprezentuje kąt obrotu etykiet podziałki. Odczyt **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Określa, ile etykiet podziałki pominąć pomiędzy rysowanymi etykietami. Zastosowane do osi kategorii lub serii. Odczyt **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Określa, ile znaczników podziałki pominąć przed narysowaniem kolejnego. Zastosowane do osi kategorii lub serii. Odczyt **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Pobiera tytuł osi. Tylko do odczytu [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Określa niestandardową wartość przedziału podprzepełnienia. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i IsUnderflowBin równa się true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# ‘is’. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje właściwie nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje właściwie nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Reprezentuje typ agregacji osi kategorii (grupowanie). Zastosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość ma zastosowanie tylko do osi kategorii i nie dotyczy wykresów 3-D. Zapisz **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Zapisz [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Określa szerokość przedziału, gdy właściwość AggregationType jest ustawiona na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Zastosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Określa typ osi kategorii. Zapisz [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Reprezentuje punkt na osi, w którym oś prostopadła ją przecina. Zapisz **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Reprezentuje CrossType na określonej osi, w której inna oś ją przecina. Zapisz [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Zapisz [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Określa, czy oś ma widoczny tytuł. Zapisz **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Zapisz **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Zapisz **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. Zapisz **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Zapisz **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Określa automatyczną wartość przedziału przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Określa automatyczną wartość odstępu etykiet podziałki. Jeśli false: użyj właściwości TickLabelSpacing. Zapisz **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Określa automatyczną wartość odstępu znaczników podziałki. Jeśli false: użyj właściwości TickMarksSpacing. Zapisz **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Określa automatyczną wartość przedziału podprzepełnienia. Jeśli false: użyj właściwości UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Zapisz **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Wskazuje, czy format jest połączony z danymi źródłowymi. Zapisz **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Określa, czy zastosowano przedział przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość przedziału przepełnienia. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Reprezentuje, czy MS PowerPoint rysuje punkty danych od końca do początku. Zapisz **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Określa, czy zastosowano przedział podprzepełnienia. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość przedziału podprzepełnienia. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Reprezentuje, czy oś jest widoczna. Zapisz **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Określa odległość etykiet od osi. Zastosowane do osi kategorii lub daty. Wartość musi być pomiędzy 0 % a 1000 %. Zapisz **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Zapisz **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Reprezentuje typ głównego znacznika podziałki dla określonej osi. Zapisz [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Reprezentuje jednostki główne dla osi daty lub wartości. Zapisz **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Reprezentuje skalę jednostki głównej dla osi daty. Zapisz [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Reprezentuje maksymalną wartość na osi wartości. Zapisz **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Reprezentuje typ mniejszego znacznika podziałki dla określonej osi. Zapisz [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Reprezentuje jednostki mniejsze dla osi daty lub wartości. Zapisz **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Reprezentuje skalę jednostki głównej dla osi daty. Zapisz [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Reprezentuje minimalną wartość na osi wartości. Zapisz **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Reprezentuje ciąg formatu dla etykiet [Axis](./). Zapisz [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Określa liczbę przedziałów, gdy wartość właściwości AggregationType jest ustawiona na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Zastosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Określa niestandardową wartość przedziału przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i IsOverflowBin równa się true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Reprezentuje pozycję osi. Zapisz [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Reprezentuje pozycję etykiet znaczników podziałki na określonej osi. Zapisz [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Reprezentuje kąt obrotu etykiet podziałki. Zapisz **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Określa, ile etykiet podziałki pominąć pomiędzy rysowanymi etykietami. Zastosowane do osi kategorii lub serii. Zapisz **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Określa, ile znaczników podziałki pominąć przed narysowaniem kolejnego. Zastosowane do osi kategorii lub serii. Zapisz **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Określa niestandardową wartość przedziału podprzepełnienia. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i IsUnderflowBin równa się true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Ustawia właściwość IAxis::get(set)_CategoryAxisType na wartość automatycznie określoną na podstawie danych osi. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ustawia n-argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [DomObject](../../aspose.slides/domobject/)
* Klasa [IAxis](../iaxis/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)