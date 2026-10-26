---
title: Axis
second_title: Aspose.Slides pro C++ API Reference
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 14
url: /cs/aspose.slides.charts/axis/
---
## Axis třída

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Metody

| Method | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečnou hodnotu. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Určuje skutečné měřítko hlavní jednotky osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečnou hodnotu. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečnou hodnotu. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Určuje skutečnou menší jednotku osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečnou hodnotu. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Určuje skutečné měřítko menší jednotky osy. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečnou hodnotu. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečnou hodnotu. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Reprezentuje typ agregace osy kategorií (seskupování). Použito na kategoriích. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje jen na osy kategorií a neplatí pro 3-D grafy. Čte **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Určuje nejmenší časovou jednotku, která je zobrazena na datumové ose. Čte [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Použito na osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Určuje typ osy kategorií. Čte [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací nadřazený graf. Pouze pro čtení [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Reprezentuje bod na ose, kde ji protíná kolmá osa. Čte **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Reprezentuje typ průniku (CrossType) na zadané ose, kde ji protíná druhá osa. Čte [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. Čte [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Reprezentuje formát osy. Pouze pro čtení [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Určuje, zda má osa viditelný název. Čte **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Udává, zda je hlavní jednotka osy přiřazena automaticky. Čte **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Udává, zda je maximální hodnota přiřazena automaticky. Čte **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Udává, zda je menší jednotka osy přiřazena automaticky. Čte **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Udává, zda je minimální hodnota přiřazena automaticky. Čte **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Určuje automatickou hodnotu overflow binu. Pokud je false: použijte vlastnost OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Určuje automatickou hodnotu mezery popisků osy. Pokud je false: použijte vlastnost TickLabelSpacing. Čte **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Určuje automatickou hodnotu mezery značek osy. Pokud je false: použijte vlastnost TickMarksSpacing. Čte **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Určuje automatickou hodnotu underflow binu. Pokud je false: použijte vlastnost UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Určuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Čte **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Udává, zda je formát propojen s daty zdroje. Čte **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Určuje, zda je použit overflow bin. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty overflow binu. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čte **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Určuje, zda je použit underflow bin. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty underflow binu. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Určuje, zda je osa viditelná. Čte **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Určuje vzdálenost popisků od osy. Použito na osy kategorií nebo datumů. Hodnota musí být mezi 0 % a 1000 %. Čte **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čte **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Reprezentuje formát hlavních mřížek na ose grafu. Pouze pro čtení [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Reprezentuje typ hlavní značky osy pro zadanou osu. Čte [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Reprezentuje hlavní jednotky pro datumovou nebo hodnotovou osu. Čte **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Reprezentuje měřítko hlavní jednotky pro datumovou osu. Čte [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Reprezentuje maximální hodnotu na ose hodnot. Čte **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Reprezentuje formát menších mřížek na ose grafu. Pouze pro čtení [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Reprezentuje typ menší značky osy pro zadanou osu. Čte [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Reprezentuje menší jednotky pro datumovou nebo hodnotovou osu. Čte **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Reprezentuje měřítko hlavní jednotky pro datumovou osu. Čte [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Reprezentuje minimální hodnotu na ose hodnot. Čte **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Reprezentuje řetězec formátu pro popisky [Axis](./). Čte [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Použito na osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Určuje vlastní hodnotu overflow binu. Použito, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Reprezentuje pozici osy. Čte [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Pro skrytí hlavní mřížky nastavte [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() na [FillType::NoFill](../../aspose.slides/filltype/). Pouze pro čtení **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Pro skrytí menší mřížky nastavte [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() na [FillType::NoFill](../../aspose.slides/filltype/). Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Reprezentuje formát textu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Reprezentuje pozici popisků značek na zadané ose. Čte [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Reprezentuje úhlový natočení popisků. Čte **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Určuje, kolik popisků se má přeskočit mezi vykreslenými popisky. Použito na osu kategorií nebo sérií. Čte **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Určuje, kolik značek se má přeskočit před vykreslením další. Použito na osu kategorií nebo sérií. Čte **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Získává název osy. Pouze pro čtení [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Určuje vlastní hodnotu underflow binu. Použito, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Reprezentuje typ agregace osy kategorií (seskupování). Použito na kategoriích. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje jen na osy kategorií a neplatí pro 3-D grafy. Zapisuje **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Určuje nejmenší časovou jednotku, která je zobrazena na datumové ose. Zapisuje [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Použito na osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Určuje typ osy kategorií. Zapisuje [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Reprezentuje bod na ose, kde ji protíná kolmá osa. Zapisuje **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Reprezentuje typ průniku (CrossType) na zadané ose, kde ji protíná druhá osa. Zapisuje [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. Zapisuje [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Určuje, zda má osa viditelný název. Zapisuje **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Udává, zda je hlavní jednotka osy přiřazena automaticky. Zapisuje **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Udává, zda je maximální hodnota přiřazena automaticky. Zapisuje **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Udává, zda je menší jednotka osy přiřazena automaticky. Zapisuje **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Udává, zda je minimální hodnota přiřazena automaticky. Zapisuje **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Určuje automatickou hodnotu overflow binu. Pokud je false: použijte vlastnost OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Určuje automatickou hodnotu mezery popisků osy. Pokud je false: použijte vlastnost TickLabelSpacing. Zapisuje **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Určuje automatickou hodnotu mezery značek osy. Pokud je false: použijte vlastnost TickMarksSpacing. Zapisuje **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Určuje automatickou hodnotu underflow binu. Pokud je false: použijte vlastnost UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Určuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Zapisuje **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Udává, zda je formát propojen s daty zdroje. Zapisuje **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Určuje, zda je použit overflow bin. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty overflow binu. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Zapisuje **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Určuje, zda je použit underflow bin. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty underflow binu. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Určuje, zda je osa viditelná. Zapisuje **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Určuje vzdálenost popisků od osy. Použito na osy kategorií nebo datumů. Hodnota musí být mezi 0 % a 1000 %. Zapisuje **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Zapisuje **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Reprezentuje typ hlavní značky osy pro zadanou osu. Zapisuje [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Reprezentuje hlavní jednotky pro datumovou nebo hodnotovou osu. Zapisuje **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Reprezentuje měřítko hlavní jednotky pro datumovou osu. Zapisuje [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Reprezentuje maximální hodnotu na ose hodnot. Zapisuje **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Reprezentuje typ menší značky osy pro zadanou osu. Zapisuje [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Reprezentuje menší jednotky pro datumovou nebo hodnotovou osu. Zapisuje **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Reprezentuje měřítko hlavní jednotky pro datumovou osu. Zapisuje [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Reprezentuje minimální hodnotu na ose hodnot. Zapisuje **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Reprezentuje řetězec formátu pro popisky [Axis](./). Zapisuje [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Použito na osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Určuje vlastní hodnotu overflow binu. Použito, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Reprezentuje pozici osy. Zapisuje [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Reprezentuje pozici popisků značek na zadané ose. Zapisuje [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Reprezentuje úhlový natočení popisků. Zapisuje **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Určuje, kolik popisků se má přeskočit mezi vykreslenými popisky. Použito na osu kategorií nebo sérií. Zapisuje **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Určuje, kolik značek se má přeskočit před vykreslením další. Použito na osu kategorií nebo sérií. Zapisuje **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Určuje vlastní hodnotu underflow binu. Použito, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Nastavuje IAxis::get(set)_CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [DomObject](../../aspose.slides/domobject/)
* Třída [IAxis](../iaxis/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)