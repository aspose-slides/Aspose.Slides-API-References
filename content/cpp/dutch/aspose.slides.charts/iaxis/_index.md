---
title: IAxis
second_title: Aspose.Slides voor C++ API-referentie
description: Omvat het object dat een as van een diagram vertegenwoordigt.
type: docs
weight: 534
url: /nl/aspose.slides.charts/iaxis/
---
## IAxis klasse


Omvat het object dat een as van een diagram vertegenwoordigt.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendkommagetaling waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een andere waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendkommagetaling waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een andere waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Specificeert de werkelijke grote eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Specificeert de werkelijke schaal van de grote eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Specificeert de werkelijke maximale waarde op de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Specificeert de werkelijke kleine eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Specificeert de werkelijke schaal van de kleine eenheid van de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Specificeert de werkelijke minimale waarde op de as. Roep eerder methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan om de werkelijke waarde te verkrijgen. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Stelt het aggregatietype van de categorieas (bins) voor. Toegepast op categorie. Alleen te gebruiken met Histogram- of HistogramPareto-reeksen. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Geeft aan of de waardeas de categorieas tussen categorieën kruist. Deze eigenschap geldt alleen voor categorieassen en niet voor 3D-diagrammen. Lees **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. Lees [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Specificeert de binbreedte wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Toegepast op categorieassen. Alleen te gebruiken met Histogram- of HistogramPareto-reeksen. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Specificeert het type van de categorieas. Lees [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert het diagram. Alleen-lezen [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Geeft het punt op de as weer waar de loodrechte as deze kruist. Lees **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Geeft het CrossType op de opgegeven as weer waar de andere as kruist. Lees [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Specificeert de schaalwaarde van de weergave-eenheden voor de waardeas. Lees [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Stelt het formaat van de as voor. Alleen-lezen [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Bepaalt of een as een zichtbare titel heeft. Lees **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Geeft aan of de grote eenheid van de as automatisch wordt toegewezen. Lees **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Geeft aan of de maximale waarde automatisch wordt toegewezen. Lees **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Geeft aan of de kleine eenheid van de as automatisch wordt toegewezen. Lees **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Geeft aan of de minimale waarde automatisch wordt toegewezen. Lees **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Specificeert automatische overflow-binwaarde. Indien false: gebruik OverflowBin-eigenschap. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Specificeert automatische waarde voor tick-label-spatiëring. Indien false: gebruik TickLabelSpacing-eigenschap. Lees **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Specificeert automatische waarde voor tick-mark-spatiëring. Indien false: gebruik TickMarksSpacing-eigenschap. Lees **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Specificeert automatische underflow-binwaarde. Indien false: gebruik UnderflowBin-eigenschap. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Geeft aan of het schaaltype van de waardeas logaritmisch is of niet. Lees **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Geeft aan of het formaat gekoppelde brongegevens zijn. Lees **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Specificeert of overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. Lees **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Specificeert of underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Geeft aan of de as zichtbaar is. Lees **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datumas. Waarde moet tussen 0% en 1000% liggen. Lees **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Geeft de logaritmische basis weer. Standaardwaarde is 10. Lees **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Stelt het formaat van de hoofdgridlijnen op een diagramas voor. Alleen-lezen [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Stelt het type van de hoofd-tick-markering voor de opgegeven as voor. Lees [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Geeft de hoofd-eenheden voor de datum- of waardeas weer. Lees **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Stelt de schaal van de hoofd-eenheid voor de datumas voor. Lees [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Geeft de maximale waarde op de waardeas weer. Lees **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Stelt het formaat van de kleine gridlijnen op een diagramas voor. Alleen-lezen [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Stelt het type van de kleine tick-markering voor de opgegeven as voor. Lees [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Geeft de kleine eenheden voor de datum- of waardeas weer. Lees **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Stelt de schaal van de hoofd-eenheid voor de datumas voor. Lees [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Geeft de minimale waarde op de waardeas weer. Lees **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Stelt de opmaak-string voor de [Axis](../axis/)-labels voor. Lees [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Toegepast op categorieassen. Alleen te gebruiken met Histogram- of HistogramPareto-reeksen. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Specificeert een aangepaste overflow-binwaarde. Toegepast wanneer IsAutomaticOverflowBin-eigenschap false is en IsOverflowBin-eigenschap true is. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Stelt de positie van de as voor. Lees [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Geeft aan of de hoofdgridlijnen worden getoond. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Geeft aan of de kleine gridlijnen worden getoond. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basisslide. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retourneert diagram-tekstformaat. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Stelt de positie van tick-label-markeringen op de opgegeven as voor. Lees [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Geeft de rotatiehoek van tick-labels weer. Lees **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen de getekende label. Lees **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende wordt getekend. Toegepast op categorie- of serie-as. Lees **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Haalt de titel van de as op. Alleen-lezen [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Specificeert een aangepaste underflow-binwaarde. Toegepast wanneer IsAutomaticUnderflowBin-eigenschap false is en IsUnderflowBin-eigenschap true is. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven vertegenwoordigt. Analog van de C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locken. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|   [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets echt, Initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, Initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Stelt het aggregatietype van de categorieas (bins) voor. Toegepast op categorie. Alleen te gebruiken met Histogram- of HistogramPareto-reeksen. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Geeft aan of de waardeas de categorieas tussen categorieën kruist. Deze eigenschap geldt alleen voor categorieassen en niet voor 3D-diagrammen. Schrijf **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. Schrijf [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Specificeert de binbreedte wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Toegepast op categorieassen. Alleen te gebruiken met Histogram- of HistogramPareto-reeksen. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Specificeert het type van de categorieas. Schrijf [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Geeft het punt op de as weer waar de loodrechte as deze kruist. Schrijf **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Geeft het CrossType op de opgegeven as weer waar de andere as kruist. Schrijf [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardeas. Schrijf [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Bepaalt of een as een zichtbare titel heeft. Schrijf **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Geeft aan of de grote eenheid van de as automatisch wordt toegewezen. Schrijf **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Geeft aan of de maximale waarde automatisch wordt toegewezen. Schrijf **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Geeft aan of de kleine eenheid van de as automatisch wordt toegewezen. Schrijf **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Geeft aan of de minimale waarde automatisch wordt toegewezen. Schrijf **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Specificeert automatische overflow-binwaarde. Indien false: gebruik OverflowBin-eigenschap. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Specificeert automatische tick-label-spatiëringswaarde. Indien false: gebruik TickLabelSpacing-eigenschap. Schrijf **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Specificeert automatische tick-mark-spatiëringswaarde. Indien false: gebruik TickMarksSpacing-eigenschap. Schrijf **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Specificeert automatische underflow-binwaarde. Indien false: gebruik UnderflowBin-eigenschap. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Geeft aan of het schaaltype van de waardeas logaritmisch is of niet. Schrijf **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Geeft aan of het formaat gekoppelde brongegevens zijn. Schrijf **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Specificeert of overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. Schrijf **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Specificeert of underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Geeft aan of de as zichtbaar is. Schrijf **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datumas. Waarde moet tussen 0% en 1000% liggen. Schrijf **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Geeft de logaritmische basis weer. Standaardwaarde is 10. Schrijf **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Stelt het type van de hoofd-tick-markering voor de opgegeven as voor. Schrijf [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Geeft de hoofd-eenheden voor de datum- of waardeas weer. Schrijf **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Stelt de schaal van de hoofd-eenheid voor de datumas voor. Schrijf [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Geeft de maximale waarde op de waardeas weer. Schrijf **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Stelt het type van de kleine tick-markering voor de opgegeven as voor. Schrijf [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Geeft de kleine eenheden voor de datum- of waardeas weer. Schrijf **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Stelt de schaal van de hoofd-eenheid voor de datumas voor. Schrijf [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Geeft de minimale waarde op de waardeas weer. Schrijf **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Stelt de opmaak-string voor de [Axis](../axis/)-labels voor. Schrijf [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Toegepast op categorieassen. Alleen te gebruiken met Histogram- of HistogramPareto-reeksen. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Specificeert een aangepaste overflow-binwaarde. Toegepast wanneer IsAutomaticOverflowBin-eigenschap false is en IsOverflowBin-eigenschap true is. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Stelt de positie van de as voor. Schrijf [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Stelt de positie van tick-label-markeringen op de opgegeven as voor. Schrijf [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Geeft de rotatiehoek van tick-labels weer. Schrijf **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen de getekende label. Schrijf **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende wordt getekend. Toegepast op categorie- of serie-as. Schrijf **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Specificeert een aangepaste underflow-binwaarde. Toegepast wanneer IsAutomaticUnderflowBin-eigenschap false is en IsUnderflowBin-eigenschap true is. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Stelt IAxis::get(set)_CategoryAxisType-eigenschap in met een waarde die automatisch wordt bepaald op basis van as-data. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement unlocken. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)