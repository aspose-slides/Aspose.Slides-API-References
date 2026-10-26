---
title: IAxis
second_title: Aspose.Slides dla C++ - referencja API
description: Zawiera obiekt, który reprezentuje oś wykresu.
type: docs
weight: 534
url: /pl/aspose.slides.charts/iaxis/
---
## Klasa IAxis

Zawiera obiekt, który reprezentuje oś wykresu.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Określa rzeczywistą główną jednostkę osi. Najpierw wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/), aby uzyskać rzeczywistą wartość. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Określa rzeczywistą skalę głównej jednostki osi. Najpierw wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/), aby uzyskać rzeczywistą wartość. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Określa rzeczywistą maksymalną wartość na osi. Najpierw wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/), aby uzyskać rzeczywistą wartość. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Określa rzeczywistą mniejszą jednostkę osi. Najpierw wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/), aby uzyskać rzeczywistą wartość. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Określa rzeczywistą skalę mniejszej jednostki osi. Najpierw wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/), aby uzyskać rzeczywistą wartość. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Określa rzeczywistą minimalną wartość na osi. Najpierw wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/), aby uzyskać rzeczywistą wartość. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość dotyczy tylko osi kategorii i nie ma zastosowania do wykresów 3-D. Odczytaj **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczytaj [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Określa szerokość kosza, gdy wartość właściwości AggregationType ustawiona na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Określa typ osi kategorii. Odczytaj [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Reprezentuje punkt na osi, w którym przecina ją oś prostopadła. Odczytaj **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Reprezentuje typ przecięcia na określonej osi, gdzie przecina ją inna oś. Odczytaj [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Odczytaj [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Reprezentuje format osi. Tylko do odczytu [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Określa, czy oś ma widoczny tytuł. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Wskazuje, czy główna jednostka osi jest przydzielana automatycznie. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Wskazuje, czy maksymalna wartość jest przydzielana automatycznie. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Wskazuje, czy mniejsza jednostka osi jest przydzielana automatycznie. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Wskazuje, czy minimalna wartość jest przydzielana automatycznie. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Określa automatyczną wartość kosza przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Określa automatyczną wartość odstępu etykiet tick. Jeśli false: użyj właściwości TickLabelSpacing. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Określa automatyczną wartość odstępu znaczników tick. Jeśli false: użyj właściwości TickMarksSpacing. Odczytaj **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Określa automatyczną wartość kosza podprzepływu. Jeśli false: użyj właściwości UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Odczytaj **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczytaj **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Określa, czy zastosowano kosz przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość kosza przepełnienia. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczytaj **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Określa, czy zastosowano kosz podprzepływu. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość kosza podprzepływu. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Reprezentuje, czy oś jest widoczna. Odczytaj **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi wynosić od 0 % do 1000 %. Odczytaj **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczytaj **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Reprezentuje format głównych linii siatki na osi wykresu. Tylko do odczytu [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Reprezentuje typ głównego znacznika tick dla określonej osi. Odczytaj [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Reprezentuje główne jednostki dla osi daty lub wartości. Odczytaj **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Reprezentuje skalę głównej jednostki dla osi daty. Odczytaj [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Reprezentuje maksymalną wartość na osi wartości. Odczytaj **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Reprezentuje format mniejszych linii siatki na osi wykresu. Tylko do odczytu [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Reprezentuje typ mniejszego znacznika tick dla określonej osi. Odczytaj [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Reprezentuje mniejsze jednostki dla osi daty lub wartości. Odczytaj **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Reprezentuje skalę głównej jednostki dla osi daty. Odczytaj [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Reprezentuje minimalną wartość na osi wartości. Odczytaj **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Reprezentuje ciąg formatu dla etykiet [Axis](../axis/). Odczytaj [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Określa liczbę koszy, gdy wartość właściwości AggregationType ustawiona na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Określa niestandardową wartość kosza przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin ustawiona jest na false i właściwość IsOverflowBin równa się true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Reprezentuje pozycję osi. Odczytaj [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Reprezentuje, czy główne linie siatki są wyświetlane. Tylko do odczytu **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Reprezentuje, czy mniejsze linie siatki są wyświetlane. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Zwraca slajd bazowy. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Zwraca format tekstu wykresu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Reprezentuje pozycję etykiet znaczników tick na określonej osi. Odczytaj [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Reprezentuje kąt obrotu etykiet tick. Odczytaj **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Określa, ile etykiet tick pominąć pomiędzy rysowanymi etykietami. Odczytaj **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Określa, ile znaczników tick pominięto przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Odczytaj **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Pobiera tytuł osi. Tylko do odczytu [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Określa niestandardową wartość kosza podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin ustawiona jest na false i właściwość IsUnderflowBin równa się true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązanej z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogia wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogia operatora C# „is”. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji klas pochodnych. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji klas pochodnych. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego z nullptr przez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość dotyczy tylko osi kategorii i nie ma zastosowania do wykresów 3-D. Zapisz **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Zapisz [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Określa szerokość kosza, gdy wartość właściwości AggregationType ustawiona na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Określa typ osi kategorii. Zapisz [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Reprezentuje punkt na osi, w którym przecina ją oś prostopadła. Zapisz **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Reprezentuje typ przecięcia na określonej osi, gdzie przecina ją inna oś. Zapisz [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Zapisz [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Określa, czy oś ma widoczny tytuł. Zapisz **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Wskazuje, czy główna jednostka osi jest przydzielana automatycznie. Zapisz **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Wskazuje, czy maksymalna wartość jest przydzielana automatycznie. Zapisz **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Wskazuje, czy mniejsza jednostka osi jest przydzielana automatycznie. Zapisz **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Wskazuje, czy minimalna wartość jest przydzielana automatycznie. Zapisz **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Określa automatyczną wartość kosza przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Określa automatyczną wartość odstępu etykiet tick. Jeśli false: użyj właściwości TickLabelSpacing. Zapisz **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Określa automatyczną wartość odstępu znaczników tick. Jeśli false: użyj właściwości TickMarksSpacing. Zapisz **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Określa automatyczną wartość kosza podprzepływu. Jeśli false: użyj właściwości UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Zapisz **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Wskazuje, czy format jest powiązany z danymi źródłowymi. Zapisz **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Określa, czy zastosowano kosz przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość kosza przepełnienia. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Zapisz **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Określa, czy zastosowano kosz podprzepływu. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość kosza podprzepływu. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Reprezentuje, czy oś jest widoczna. Zapisz **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi wynosić od 0 % do 1000 %. Zapisz **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Zapisz **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Reprezentuje typ głównego znacznika tick dla określonej osi. Zapisz [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Reprezentuje główne jednostki dla osi daty lub wartości. Zapisz **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Reprezentuje skalę głównej jednostki dla osi daty. Zapisz [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Reprezentuje maksymalną wartość na osi wartości. Zapisz **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Reprezentuje typ mniejszego znacznika tick dla określonej osi. Zapisz [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Reprezentuje mniejsze jednostki dla osi daty lub wartości. Zapisz **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Reprezentuje skalę głównej jednostki dla osi daty. Zapisz [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Reprezentuje minimalną wartość na osi wartości. Zapisz **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Reprezentuje ciąg formatu dla etykiet [Axis](../axis/). Zapisz [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Określa liczbę koszy, gdy wartość właściwości AggregationType ustawiona na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Określa niestandardową wartość kosza przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin ustawiona jest na false i właściwość IsOverflowBin równa się true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Reprezentuje pozycję osi. Zapisz [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Reprezentuje pozycję etykiet znaczników tick na określonej osi. Zapisz [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Reprezentuje kąt obrotu etykiet tick. Zapisz **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Określa, ile etykiet tick pominąć pomiędzy rysowanymi etykietami. Zapisz **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Określa, ile znaczników tick pominięto przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Zapisz **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Określa niestandardową wartość kosza podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin ustawiona jest na false i właściwość IsUnderflowBin równa się true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Ustawia właściwość IAxis::get(set)_CategoryAxisType na wartość automatycznie określoną na podstawie danych osi. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość współlicznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednie; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz również

* Class [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)