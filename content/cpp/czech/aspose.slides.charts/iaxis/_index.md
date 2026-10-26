---
title: IAxis
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 534
url: /cs/aspose.slides.charts/iaxis/
---
## IAxis třída

Zapouzdřuje objekt, který představuje osu grafu.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečné hodnoty. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Určuje skutečné měřítko hlavní jednotky osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečné hodnoty. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečné hodnoty. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Určuje skutečnou minor jednotku osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečné hodnoty. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Určuje skutečné měřítko minor jednotky osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečné hodnoty. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečné hodnoty. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Reprezentuje typ agregace osy kategorií (binning). Použito u kategorie. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Reprezentuje, zda osa hodnot překračuje osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje pouze na osy kategorií a neplatí pro 3-D grafy. Čte **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Určuje nejmenší časovou jednotku, která je zobrazena na časové ose. Čte [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Použito u os kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Určuje typ osy kategorií. Čte [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Vrací graf. Pouze ke čtení [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Reprezentuje bod na ose, kde ji protichůdná osa protíná. Čte **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Reprezentuje CrossType na zadané ose, kde ji protichůdná osa protíná. Čte [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Určuje měřítko zobrazovacích jednotek pro osu hodnot. Čte [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Reprezentuje formát osy. Pouze ke čtení [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Určuje, zda má osa viditelný název. Čte **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Čte **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indikuje, zda je maximální hodnota přiřazena automaticky. Čte **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indikuje, zda je minor jednotka osy přiřazena automaticky. Čte **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indikuje, zda je minimální hodnota přiřazena automaticky. Čte **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Určuje automatickou hodnotu overflow koše. Pokud false: použijte vlastnost OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Určuje automatické rozestupy popisků značek. Pokud false: použijte vlastnost TickLabelSpacing. Čte **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Určuje automatické rozestupy značek měřítka. Pokud false: použijte vlastnost TickMarksSpacing. Čte **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Určuje automatickou hodnotu underflow koše. Pokud false: použijte vlastnost UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Reprezentuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Čte **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indikuje, zda je formát propojen s daty zdroje. Čte **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Určuje, zda je použita overflow koš. Použijte IsAutomaticOverflowBin a OverflowBin pro nastavení hodnoty overflow koše. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního po první. Čte **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Určuje, zda je použita underflow koš. Použijte IsAutomaticUnderflowBin a UnderflowBin pro nastavení hodnoty underflow koše. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Reprezentuje, zda je osa viditelná. Čte **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Určuje vzdálenost popisků od osy. Použito u osy kategorie nebo data. Hodnota musí být mezi 0 % a 1000 %. Čte **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čte **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Reprezentuje formát hlavních mřížek na ose grafu. Pouze ke čtení [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Reprezentuje typ hlavní značky měřítka pro zadanou osu. Čte [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Reprezentuje hlavní jednotky pro časovou nebo hodnotovou osu. Čte **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Reprezentuje měřítko hlavní jednotky pro časovou osu. Čte [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Reprezentuje maximální hodnotu na ose hodnot. Čte **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Reprezentuje formát minor mřížek na ose grafu. Pouze ke čtení [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Reprezentuje typ minor značky měřítka pro zadanou osu. Čte [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Reprezentuje minor jednotky pro časovou nebo hodnotovou osu. Čte **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Reprezentuje měřítko hlavní jednotky pro časovou osu. Čte [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Reprezentuje minimální hodnotu na ose hodnot. Čte **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Určuje formátovací řetězec pro popisky [Axis](../axis/). Čte [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Použito u os kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Určuje vlastní hodnotu pro overflow koš. Použita, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin má hodnotu true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Reprezentuje polohu osy. Čte [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze ke čtení [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Reprezentuje, zda jsou zobrazeny hlavní mřížky. Pouze ke čtení **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Reprezentuje, zda jsou zobrazeny minor mřížky. Pouze ke čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Vrací základní snímek. Pouze ke čtení [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Vrací formát textu grafu. Pouze ke čtení [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Reprezentuje polohu popisků značek měřítka na zadané ose. Čte [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Reprezentuje úhel otočení popisků značek. Čte **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Určuje, kolik popisků značek přeskočit mezi vykreslenými popisky. Čte **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Určuje, kolik značek měřítka přeskočit před tím, než bude vykreslena další. Použito u osy kategorie nebo řady. Čte **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Získá název osy. Pouze ke čtení [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Určuje vlastní hodnotu pro underflow koš. Použita, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin má hodnotu true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje uzamykání pomocí C# lock(). Zavolejte přímo nebo použijte strážní objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Reprezentuje typ agregace osy kategorií (binning). Použito u kategorie. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Reprezentuje, zda osa hodnot překračuje osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje pouze na osy kategorií a neplatí pro 3-D grafy. Zapíše **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Určuje nejmenší časovou jednotku, která je zobrazena na časové ose. Zapíše [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Použito u os kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Určuje typ osy kategorií. Zapíše [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Reprezentuje bod na ose, kde ji protichůdná osa protíná. Zapíše **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Reprezentuje CrossType na zadané ose, kde ji protichůdná osa protíná. Zapíše [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Určuje měřítko zobrazovacích jednotek pro osu hodnot. Zapíše [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Určuje, zda má osa viditelný název. Zapíše **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Zapíše **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indikuje, zda je maximální hodnota přiřazena automaticky. Zapíše **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indikuje, zda je minor jednotka osy přiřazena automaticky. Zapíše **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indikuje, zda je minimální hodnota přiřazena automaticky. Zapíše **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Určuje automatickou hodnotu overflow koše. Pokud false: použijte vlastnost OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Určuje automatické rozestupy popisků značek. Pokud false: použijte vlastnost TickLabelSpacing. Zapíše **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Určuje automatické rozestupy značek měřítka. Pokud false: použijte vlastnost TickMarksSpacing. Zapíše **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Určuje automatickou hodnotu underflow koše. Pokud false: použijte vlastnost UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Reprezentuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Zapíše **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indikuje, zda je formát propojen s daty zdroje. Zapíše **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Určuje, zda je použita overflow koš. Použijte IsAutomaticOverflowBin a OverflowBin pro nastavení hodnoty overflow koše. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního po první. Zapíše **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Určuje, zda je použita underflow koš. Použijte IsAutomaticUnderflowBin a UnderflowBin pro nastavení hodnoty underflow koše. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Reprezentuje, zda je osa viditelná. Zapíše **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Určuje vzdálenost popisků od osy. Použito u osy kategorie nebo data. Hodnota musí být mezi 0 % a 1000 %. Zapíše **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Zapíše **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Reprezentuje typ hlavní značky měřítka pro zadanou osu. Zapíše [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Reprezentuje hlavní jednotky pro časovou nebo hodnotovou osu. Zapíše **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Reprezentuje měřítko hlavní jednotky pro časovou osu. Zapíše [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Reprezentuje maximální hodnotu na ose hodnot. Zapíše **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Reprezentuje typ minor značky měřítka pro zadanou osu. Zapíše [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Reprezentuje minor jednotky pro časovou nebo hodnotovou osu. Zapíše **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Reprezentuje měřítko hlavní jednotky pro časovou osu. Zapíše [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Reprezentuje minimální hodnotu na ose hodnot. Zapíše **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Reprezentuje formátovací řetězec pro popisky [Axis](../axis/). Zapíše [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Použito u os kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Určuje vlastní hodnotu pro overflow koš. Použita, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin má hodnotu true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Reprezentuje polohu osy. Zapíše [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Reprezentuje polohu popisků značek měřítka na zadané ose. Zapíše [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Reprezentuje úhel otočení popisků značek. Zapíše **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Určuje, kolik popisků značek přeskočit mezi vykreslenými popisky. Zapíše **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Určuje, kolik značek měřítka přeskočit před tím, než bude vykreslena další. Použito u osy kategorie nebo řady. Zapíše **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Určuje vlastní hodnotu pro underflow koš. Použita, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin má hodnotu true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Nastaví vlastnost IAxis::get(set)_CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte strážní objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Class [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)