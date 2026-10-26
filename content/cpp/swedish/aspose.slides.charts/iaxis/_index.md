---
title: IAxis
second_title: Aspose.Slides för C++ API-referens
description: Inkapslar objektet som representerar ett diagramaxel.
type: docs
weight: 534
url: /sv/aspose.slides.charts/iaxis/
---
## IAxis klass

Inkapslar objektet som representerar ett diagramaxel.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Anger den faktiska huvudenheten för axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Anger den faktiska skalan för huvudenheten på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Anger det faktiska maximivärdet på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Anger den faktiska delenheten för axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Anger den faktiska skalan för delenheten på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Anger det faktiska minimivärdet på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Representerar aggregeringstypen för kategori-axeln (binning). Tillämpas på kategori. Endast använd med Histogram- eller HistogramPareto-serier. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Representerar om värdeaxeln korsar kategori-axeln mellan kategorier. Denna egenskap gäller endast för kategori-axlar och gäller inte för 3-D-diagram. Läs **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Anger den minsta tidsenheten som representeras på datumaxeln. Läs [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Anger bin-bredden när egenskapen AggregationType har värdet [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Tillämpligt på kategori-axlar. Endast använd med Histogram- eller HistogramPareto-serier. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Anger typen av kategori-axeln. Läs [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Skrivskyddad [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Anger skalningsvärdet för visningsenheterna på värdeaxeln. Läs [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Representerar formatet för axeln. Skrivskyddad [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Avgör om en axel har en synlig titel. Läs **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indikerar om huvudenheten för axeln tilldelas automatiskt. Läs **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indikerar om maxvärdet tilldelas automatiskt. Läs **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indikerar om delenheten för axeln tilldelas automatiskt. Läs **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indikerar om minvärdet tilldelas automatiskt. Läs **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Anger automatiskt overflow-bin-värde. Om falskt: använd egenskapen OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Anger automatiskt avstånd mellan tick-etiketter. Om falskt: använd egenskapen TickLabelSpacing. Läs **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Anger automatiskt avstånd mellan tick-markeringar. Om falskt: använd egenskapen TickMarksSpacing. Läs **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Anger automatiskt underflow-bin-värde. Om falskt: använd egenskapen UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Representerar om skala-typen för värdeaxeln är logaritmisk eller inte. Läs **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indikerar om formatet är länkat till källdata. Läs **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Representerar om axeln är synlig. Läs **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Anger avståndet för etiketter från axeln. Tillämpligt på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Läs **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Representerar den logaritmiska basen. Standardvärdet är 10. Läs **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Representerar formatet för huvudrutnätslinjer på en diagramaxel. Skrivskyddad [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Representerar typen av huvud-tick-markering för den angivna axeln. Läs [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Representerar huvud-enheterna för datum- eller värdeaxeln. Läs **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Representerar skalan för huvud-enheten på datumaxeln. Läs [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Representerar maxvärdet på värdeaxeln. Läs **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Representerar formatet för mindre rutnätslinjer på en diagramaxel. Skrivskyddad [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Representerar typen av mindre tick-markering för den angivna axeln. Läs [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Representerar de mindre enheterna för datum- eller värdeaxeln. Läs **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Representerar skalan för huvud-enheten på datumaxeln. Läs [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Representerar minvärdet på värdeaxeln. Läs **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Representerar formatsträngen för [Axis](../axis/)-etiketterna. Läs [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Anger antalet bin när egenskapen AggregationType har värdet [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Tillämpligt på kategori-axlar. Endast använd med Histogram- eller HistogramPareto-serier. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Anger anpassat värde för overflow-bin. Tillämpas när egenskapen IsAutomaticOverflowBin är falsk och IsOverflowBin är sann. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Representerar axelns position. Läs [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Representerar om huvudrutnätslinjerna visas. Skrivskyddad **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Representerar om mindre rutnätslinjer visas. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grund-sliden. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returnerar diagramtextformatet. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Representerar positionen för tick-etiketterna på den angivna axeln. Läs [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Representerar rotationsvinkeln för tick-etiketterna. Läs **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Läs **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpligt på kategori- eller serier-axel. Läs **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Hämtar axelns titel. Skrivskyddad [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Anger anpassat värde för underflow-bin. Tillämpas när egenskapen IsAutomaticUnderflowBin är falsk och IsUnderflowBin är sann. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C#-metoden [Object.GetHashCode()](../../system/object/gethashcode/). Gör det möjligt att hash-a anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C#-anropet [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C#-metoden [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar gemensamt referensantal med angivet värde. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Representerar aggregeringstypen för kategori-axeln (binning). Tillämpas på kategori. Endast använd med Histogram- eller HistogramPareto-serier. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Representerar om värdeaxeln korsar kategori-axeln mellan kategorier. Denna egenskap gäller endast för kategori-axlar och gäller inte för 3-D-diagram. Skriv **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Anger den minsta tidsenheten som representeras på datumaxeln. Skriv [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Anger bin-bredden när egenskapen AggregationType har värdet [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Tillämpligt på kategori-axlar. Endast använd med Histogram- eller HistogramPareto-serier. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Anger typen av kategori-axeln. Skriv [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Representerar punkten på axeln där den vinkelräta axeln korsar den. Skriv **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Representerar CrossType på den angivna axeln där den andra axeln korsar. Skriv [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Anger skalningsvärdet för visningsenheterna på värdeaxeln. Skriv [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Avgör om en axel har en synlig titel. Skriv **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indikerar om huvudenheten för axeln tilldelas automatiskt. Skriv **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indikerar om maxvärdet tilldelas automatiskt. Skriv **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indikerar om delenheten för axeln tilldelas automatiskt. Skriv **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indikerar om minvärdet tilldelas automatiskt. Skriv **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Anger automatiskt overflow-bin-värde. Om falskt: använd egenskapen OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Anger automatiskt avstånd mellan tick-etiketter. Om falskt: använd egenskapen TickLabelSpacing. Skriv **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Anger automatiskt avstånd mellan tick-markeringar. Om falskt: använd egenskapen TickMarksSpacing. Skriv **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Anger automatiskt underflow-bin-värde. Om falskt: använd egenskapen UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Representerar om skala-typen för värdeaxeln är logaritmisk eller inte. Skriv **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indikerar om formatet är länkat till källdata. Skriv **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Representerar om MS PowerPoint ritar datapunkter från sista till första. Skriv **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Representerar om axeln är synlig. Skriv **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Anger avståndet för etiketter från axeln. Tillämpligt på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Skriv **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Representerar den logaritmiska basen. Standardvärdet är 10. Skriv **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Representerar typen av huvud-tick-markering för den angivna axeln. Skriv [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Representerar huvud-enheterna för datum- eller värdeaxeln. Skriv **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Representerar skalan för huvud-enheten på datumaxeln. Skriv [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Representerar maxvärdet på värdeaxeln. Skriv **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Representerar typen av mindre tick-markering för den angivna axeln. Skriv [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Representerar de mindre enheterna för datum- eller värdeaxeln. Skriv **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Representerar skalan för huvud-enheten på datumaxeln. Skriv [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Representerar minvärdet på värdeaxeln. Skriv **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Representerar formatsträngen för [Axis](../axis/)-etiketterna. Skriv [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Anger antalet bin när egenskapen AggregationType har värdet [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Tillämpligt på kategori-axlar. Endast använd med Histogram- eller HistogramPareto-serier. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Anger anpassat värde för overflow-bin. Tillämpas när egenskapen IsAutomaticOverflowBin är falsk och IsOverflowBin är sann. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Representerar axelns position. Skriv [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Representerar positionen för tick-etiketterna på den angivna axeln. Skriv [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Representerar rotationsvinkeln för tick-etiketterna. Skriv **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Skriv **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpligt på kategori- eller serier-axel. Skriv **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Anger anpassat värde för underflow-bin. Tillämpas när egenskapen IsAutomaticUnderflowBin är falsk och IsUnderflowBin är sann. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Ställer in IAxis::get(set)_CategoryAxisType-egenskapen med ett värde som bestäms automatiskt baserat på axeldata. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [IFormattedTextContainer](../iformattedtextcontainer/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)