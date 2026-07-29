---
title: Axis
second_title: Aspose.Slides för C++ API-referens
description: Inkapslar objektet som representerar ett diagramaxel.
type: docs
weight: 14
url: /sv/aspose.slides.charts/axis/
---
## Axis klass

Inkapslar objektet som representerar ett diagramaxel.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Anger den faktiska huvudenheten för axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Anger den faktiska skalan för huvudenheten på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Anger det faktiska maximivärdet på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Anger den faktiska mindre enheten på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Anger den faktiska skalan för den mindre enheten på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Anger det faktiska minimivärdet på axeln. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) tidigare för att få det faktiska värdet. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Representerar aggregeringstyp för kategori-axel (binning). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Representerar om värdeaxeln korsar kategori-axeln mellan kategorier. Denna egenskap gäller endast för kategori-axlar och gäller inte för 3-D-diagram. Läs **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Anger den minsta tidsenheten som representeras på datumaxeln. Läs [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Anger binbredd när AggregationType-egenskapens värde är satt till [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Tillämpas på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Anger typen av kategori-axel. Läs [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Representerar CrossType på den specificerade axeln där den andra axeln korsar. Läs [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Anger skalningsvärdet för displayenheter för värdeaxeln. Läs [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Representerar formatet för axeln. Skrivskyddad [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Avgör om en axel har en synlig titel. Läs **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Indikerar om huvudenheten för axeln tilldelas automatiskt. Läs **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Indikerar om maxvärdet tilldelas automatiskt. Läs **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Indikerar om minvärdet tilldelas automatiskt. Läs **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Anger automatiskt overflow-bin-värde. Om falskt: använd OverflowBin-egenskapen. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Anger automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Anger automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Anger automatiskt underflow-bin-värde. Om falskt: använd UnderflowBin-egenskapen. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Representerar om skalatypen för värdeaxeln är logaritmisk eller inte. Läs **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Indikerar om formatet är länkat till källdata. Läs **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Anger om overflow-bin har tillämpats. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Anger om underflow-bin har tillämpats. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Representerar om axeln är synlig. Läs **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Läs **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Representerar den logaritmiska basen. Standardvärdet är 10. Läs **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Representerar formatet för huvudrutnäten på ett diagramaxel. Skrivskyddad [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Representerar typen av huvud-tick-markering för den specificerade axeln. Läs [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Representerar huvud-enheterna för datum- eller värdeaxeln. Läs **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Representerar skalan för huvud-enheten för datumaxeln. Läs [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Representerar maximivärdet på värdeaxeln. Läs **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Representerar formatet för mindre rutnät på ett diagramaxel. Skrivskyddad [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Representerar typen av mindre tick-markering för den specificerade axeln. Läs [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Representerar de mindre enheterna för datum- eller värdeaxeln. Läs **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Representerar skalan för huvud-enheten för datumaxeln. Läs [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Representerar minimivärdet på värdeaxeln. Läs **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Representerar formatsträngen för [Axis](./)-etiketterna. Läs [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Anger antalet bin när AggregationType-egenskapens värde är satt till [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Tillämpas på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Anger anpassat värde för overflow-bin. Tillämpas när IsAutomaticOverflowBin-egenskapen är falsk och IsOverflowBin-egenskapen är sann. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Representerar axelns position. Läs [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | För att dölja huvudrutnäten, sätt [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() till [FillType::NoFill](../../aspose.slides/filltype/). Skrivskyddad **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | För att dölja mindre rutnäten, sätt [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() till [FillType::NoFill](../../aspose.slides/filltype/). Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Representerar textformat. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Representerar positionen för tick-etikett-markeringar på den specificerade axeln. Läs [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Representerar rotationsvinkeln för tick-etiketter. Läs **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Tillämpas på kategori- eller serieraxel. Läs **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller serieraxel. Läs **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Hämtar axelns titel. Skrivskyddad [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Anger anpassat värde för underflow-bin. Tillämpas när IsAutomaticUnderflowBin-egenskapen är falsk och IsUnderflowBin-egenskapen är sann. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiering av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiering av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Representerar aggregeringstyp för kategori-axel (binning). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Representerar om värdeaxeln korsar kategori-axeln mellan kategorier. Denna egenskap gäller endast för kategori-axlar och gäller inte för 3-D-diagram. Skriv **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Anger den minsta tidsenheten som representeras på datumaxeln. Skriv [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Anger binbredd när AggregationType-egenskapens värde är satt till [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Tillämpas på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Anger typen av kategori-axel. Skriv [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Representerar punkten på axeln där den vinkelräta axeln korsar den. Skriv **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Representerar CrossType på den specificerade axeln där den andra axeln korsar. Skriv [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Anger skalningsvärdet för displayenheter för värdeaxeln. Skriv [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Avgör om en axel har en synlig titel. Skriv **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Indikerar om huvudenheten för axeln tilldelas automatiskt. Skriv **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Indikerar om maxvärdet tilldelas automatiskt. Skriv **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Indikerar om den mindre enheten för axeln tilldelas automatiskt. Skriv **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Indikerar om minvärdet tilldelas automatiskt. Skriv **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Anger automatiskt overflow-bin-värde. Om falskt: använd OverflowBin-egenskapen. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Anger automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Skriv **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Anger automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Skriv **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Anger automatiskt underflow-bin-värde. Om falskt: använd UnderflowBin-egenskapen. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Representerar om skalatypen för värdeaxeln är logaritmisk eller inte. Skriv **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Indikerar om formatet är länkat till källdata. Skriv **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Anger om overflow-bin har tillämpats. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Representerar om MS PowerPoint ritar datapunkter från sista till första. Skriv **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Anger om underflow-bin har tillämpats. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Representerar om axeln är synlig. Skriv **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Skriv **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Representerar den logaritmiska basen. Standardvärdet är 10. Skriv **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Representerar typen av huvud-tick-markering för den specificerade axeln. Skriv [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Representerar huvud-enheterna för datum- eller värdeaxeln. Skriv **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Representerar skalan för huvud-enheten för datumaxeln. Skriv [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Representerar maximivärdet på värdeaxeln. Skriv **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Representerar typen av mindre tick-markering för den specificerade axeln. Skriv [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Representerar de mindre enheterna för datum- eller värdeaxeln. Skriv **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Representerar skalan för huvud-enheten för datumaxeln. Skriv [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Representerar minimivärdet på värdeaxeln. Skriv **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Representerar formatsträngen för [Axis](./)-etiketterna. Skriv [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Anger antalet bin när AggregationType-egenskapens värde är satt till [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Tillämpas på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Anger anpassat värde för overflow-bin. Tillämpas när IsAutomaticOverflowBin-egenskapen är falsk och IsOverflowBin-egenskapen är sann. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Representerar axelns position. Skriv [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Representerar positionen för tick-etikett-markeringar på den specificerade axeln. Skriv [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Representerar rotationsvinkeln för tick-etiketter. Skriv **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Tillämpas på kategori- eller serieraxel. Skriv **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller serieraxel. Skriv **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Anger anpassat värde för underflow-bin. Tillämpas när IsAutomaticUnderflowBin-egenskapen är falsk och IsUnderflowBin-egenskapen är sann. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Ställer in IAxis::get(set)_CategoryAxisType-egenskapen med ett värde som automatiskt bestäms baserat på axeldata. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Sätt n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Se även

* Klass [DomObject](../../aspose.slides/domobject/)
* Klass [IAxis](../iaxis/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)