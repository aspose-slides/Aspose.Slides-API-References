---
title: Axis
second_title: Aspose.Slides voor C++ API-referentie
description: Omvat het object dat de as van een diagram vertegenwoordigt.
type: docs
weight: 14
url: /nl/aspose.slides.charts/axis/
---
## Axis klasse

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Bootst C#-stijl zwevendekommagetallen vergelijken na waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Bootst C#-stijl zwevendekommagetallen vergelijken na waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Specificeert de werkelijke hoofd eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Specificeert de werkelijke schaal van de hoofd eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Specificeert de werkelijke maximale waarde op de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Specificeert de werkelijke onderliggende eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Specificeert de werkelijke schaal van de onderliggende eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Specificeert de werkelijke minimale waarde op de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Vertegenwoordigt het aggregatietype van de categorie-as (binnening). Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Geeft aan of de waardenas de categorie-as tussen categorieën kruist. Deze eigenschap geldt alleen voor categorie-assen en niet voor 3D-diagrammen. Lezen **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Specificeert de kleinste tijdseenheid die wordt weergegeven op de datum-as. Lezen [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Specificeert de breedte van de bin wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Specificeert het type van de categorie-as. Lezen [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Geeft de bovenliggende diagram terug. Alleen-lezen [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Geeft het punt op de as weer waar de loodrechte as deze kruist. Lezen **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Geeft het CrossType op de opgegeven as weer waar de andere as kruist. Lezen [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Vertegenwoordigt het formaat van de as. Alleen-lezen [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Bepaalt of een as een zichtbare titel heeft. Lezen **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Geeft aan of de hoofd eenheid van de as automatisch wordt toegewezen. Lezen **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Geeft aan of de onderliggende eenheid van de as automatisch wordt toegewezen. Lezen **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Specificeert automatische overflow-binwaarde. Indien false: gebruik OverflowBin property. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Specificeert automatische afstand tussen tick-labels. Indien false: gebruik TickLabelSpacing property. Lezen **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Specificeert automatische afstand tussen tick-markeringen. Indien false: gebruik TickMarksSpacing property. Lezen **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Specificeert automatische underflow-binwaarde. Indien false: gebruik UnderflowBin property. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lezen **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Geeft aan of het formaat is gekoppeld aan brondata. Lezen **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Specificeert of overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. Lezen **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Specificeert of underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Geeft aan of de as zichtbaar is. Lezen **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Vertegenwoordigt het formaat van de hoofd-gridlijnen op een diagramas. Alleen-lezen [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Vertegenwoordigt het type van de hoofd-tickmarkering voor de opgegeven as. Lezen [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Geeft de hoofd-eenheden voor de datum- of waardenas weer. Lezen **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Vertegenwoordigt de schaal van de hoofd-eenheid voor de datum-as. Lezen [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Geeft de maximale waarde op de waardenas weer. Lezen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Vertegenwoordigt het formaat van de onderliggende gridlijnen op een diagramas. Alleen-lezen [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Vertegenwoordigt het type van de onderliggende tickmarkering voor de opgegeven as. Lezen [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Geeft de onderliggende eenheden voor de datum- of waardenas weer. Lezen **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Vertegenwoordigt de schaal van de hoofd-eenheid voor de datum-as. Lezen [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Geeft de minimale waarde op de waardenas weer. Lezen **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Vertegenwoordigt de opmaak-string voor de [Axis](./)-labels. Lezen [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Specificeert een aangepaste overflow-binwaarde. Toegepast wanneer IsAutomaticOverflowBin is ingesteld op false en IsOverflowBin true is. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Vertegenwoordigt de positie van de as. Lezen [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Om de hoofd-gridlijn te verbergen, stel [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() in op [FillType::NoFill](../../aspose.slides/filltype/). Alleen-lezen **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Om de onderliggende gridlijn te verbergen, stel [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() in op [FillType::NoFill](../../aspose.slides/filltype/). Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Vertegenwoordigt het formaat van tekst. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Vertegenwoordigt de positie van tick-labeltekens op de opgegeven as. Lezen [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Geeft de rotatiehoek van tick-labels weer. Lezen **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen de getekende label. Toegepast op categorie- of reeksen-as. Lezen **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende getekend wordt. Toegepast op categorie- of reeksen-as. Lezen **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Haalt de titel van de as op. Alleen-lezen [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Specificeert een aangepaste underflow-binwaarde. Toegepast wanneer IsAutomaticUnderflowBin is ingesteld op false en IsUnderflowBin true is. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashberekening van gepersonaliseerde objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-wachterobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van gepersonaliseerde types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Vertegenwoordigt het aggregatietype van de categorie-as (binnening). Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Geeft aan of de waardenas de categorie-as tussen categorieën kruist. Deze eigenschap geldt alleen voor categorie-assen en niet voor 3-D-diagrammen. Schrijf **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Schrijf [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Specificeert de binbreedte wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Specificeert het type van de categorie-as. Schrijf [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Geeft het punt op de as weer waar de loodrechte as deze kruist. Schrijf **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Geeft het CrossType op de opgegeven as weer waar de andere as kruist. Schrijf [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Schrijf [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Bepaalt of een as een zichtbare titel heeft. Schrijf **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. Schrijf **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Geeft aan of de maximale waarde automatisch wordt toegewezen. Schrijf **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Geeft aan of de onderliggende eenheid van de as automatisch wordt toegewezen. Schrijf **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Geeft aan of de minimale waarde automatisch wordt toegewezen. Schrijf **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Specificeert automatische overflow-binwaarde. Indien false: gebruik OverflowBin-eigenschap. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Specificeert automatische afstand tussen tick-labels. Indien false: gebruik TickLabelSpacing-eigenschap. Schrijf **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Specificeert automatische afstand tussen tick-markeringen. Indien false: gebruik TickMarksSpacing-eigenschap. Schrijf **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Specificeert automatische underflow-binwaarde. Indien false: gebruik UnderflowBin-eigenschap. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Schrijf **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Geeft aan of het formaat is gekoppeld aan brondata. Schrijf **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Specificeert of overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. Schrijf **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Specificeert of underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Geeft aan of de as zichtbaar is. Schrijf **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Schrijf **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Geeft de logaritmische basis weer. Standaardwaarde is 10. Schrijf **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Vertegenwoordigt het type van de hoofd-tickmarkering voor de opgegeven as. Schrijf [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Geeft de hoofd-eenheden voor de datum- of waardenas weer. Schrijf **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Vertegenwoordigt de schaal van de hoofd-eenheid voor de datum-as. Schrijf [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Geeft de maximale waarde op de waardenas weer. Schrijf **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Vertegenwoordigt het type van de onderliggende tickmarkering voor de opgegeven as. Schrijf [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Geeft de onderliggende eenheden voor de datum- of waardenas weer. Schrijf **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Vertegenwoordigt de schaal van de hoofd-eenheid voor de datum-as. Schrijf [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Geeft de minimale waarde op de waardenas weer. Schrijf **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Vertegenwoordigt de opmaak-string voor de [Axis](./)-labels. Schrijf [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Specificeert een aangepaste overflow-binwaarde. Toegepast wanneer IsAutomaticOverflowBin is ingesteld op false en IsOverflowBin true is. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Vertegenwoordigt de positie van de as. Schrijf [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Vertegenwoordigt de positie van tick-labeltekens op de opgegeven as. Schrijf [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Geeft de rotatiehoek van tick-labels weer. Schrijf **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen de getekende label. Toegepast op categorie- of reeksen-as. Schrijf **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende getekend wordt. Toegepast op categorie- of reeksen-as. Schrijf **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Specificeert een aangepaste underflow-binwaarde. Toegepast wanneer IsAutomaticUnderflowBin is ingesteld op false en IsUnderflowBin true is. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Stelt de eigenschap IAxis::get(set)_CategoryAxisType in met een waarde die automatisch wordt bepaald op basis van as-data. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Stelt het n'th-sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van gepersonaliseerde objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-wachterobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [IAxis](../iaxis/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)