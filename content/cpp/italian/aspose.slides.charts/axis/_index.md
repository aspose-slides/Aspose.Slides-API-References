---
title: Axis
second_title: Riferimento API di Aspose.Slides per C++
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
weight: 14
url: /it/aspose.slides.charts/axis/
---
## Axis classe

Encapsula l'oggetto che rappresenta l'asse di un grafico.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Metodi

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Specifica l'unità maggiore reale dell'asse. Chiamare prima il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Specifica la scala dell'unità maggiore reale dell'asse. Chiamare prima il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Specifica il valore massimo reale sull'asse. Chiamare prima il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Specifica l'unità minore reale dell'asse. Chiamare prima il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Specifica la scala dell'unità minore reale dell'asse. Chiamare prima il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Specifica il valore minimo reale sull'asse. Chiamare prima il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Rappresenta il tipo di aggregazione dell'asse di categoria (binning). Applicato alla categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Rappresenta se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non ai grafici 3-D. Lettura **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Specifica l'unità di tempo più piccola rappresentata sull'asse delle date. Lettura [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Specifica il tipo dell'asse di categoria. Lettura [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Restituisce il grafico padre. Solo lettura [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Rappresenta il formato dell'asse. Solo lettura [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Determina se un asse ha un titolo visibile. Lettura **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Indica se l'unità maggiore dell'asse è assegnata automaticamente. Lettura **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Indica se il valore massimo è assegnato automaticamente. Lettura **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Indica se l'unità minore dell'asse è assegnata automaticamente. Lettura **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Indica se il valore minimo è assegnato automaticamente. Lettura **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Specifica il valore automatico del bin di overflow. Se false: usare la proprietà OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Specifica il valore automatico della spaziatura delle etichette dei tic. Se false: usare la proprietà TickLabelSpacing. Lettura **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Specifica il valore automatico della spaziatura dei segni di tic. Se false: usare la proprietà TickMarksSpacing. Lettura **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Specifica il valore automatico del bin di underflow. Se false: usare la proprietà UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. Lettura **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Indica se il formato è collegato ai dati di origine. Lettura **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Specifica se il bin di overflow è applicato. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Specifica se il bin di underflow è applicato. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Rappresenta se l'asse è visibile. Lettura **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Specifica la distanza delle etichette dall'asse. Applicato agli assi di categoria o data. Il valore deve essere tra 0% e 1000%. Lettura **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Rappresenta il formato delle linee di griglia maggiori su un asse del grafico. Solo lettura [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Rappresenta il tipo di segno di tic maggiore per l'asse specificato. Lettura [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Rappresenta le unità maggiori per l'asse di data o di valore. Lettura **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Rappresenta la scala dell'unità maggiore per l'asse di data. Lettura [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Rappresenta il valore massimo sull'asse dei valori. Lettura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Rappresenta il formato delle linee di griglia minori su un asse del grafico. Solo lettura [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Rappresenta il tipo di segno di tic minore per l'asse specificato. Lettura [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Rappresenta le unità minori per l'asse di data o di valore. Lettura **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Rappresenta la scala dell'unità maggiore per l'asse di data. Lettura [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Rappresenta il valore minimo sull'asse dei valori. Lettura **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Rappresenta la stringa di formato per le etichette [Axis](./). Lettura [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata a false e la proprietà IsOverflowBin è true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Rappresenta la posizione dell'asse. Lettura [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Per nascondere la linea di griglia maggiore impostare [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() a [FillType::NoFill](../../aspose.slides/filltype/). Solo lettura **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Per nascondere la linea di griglia minore impostare [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() a [FillType::NoFill](../../aspose.slides/filltype/). Solo lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Rappresenta il formato del testo. Solo lettura [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Rappresenta la posizione delle etichette dei segni di tic sull'asse specificato. Lettura [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Rappresenta l'angolo di rotazione delle etichette dei tic. Lettura **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Specifica quante etichette di tic saltare tra le etichette disegnate. Applicato agli assi di categoria o di serie. Lettura **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Specifica quanti segni di tic devono essere saltati prima di disegnarne il successivo. Applicato agli assi di categoria o di serie. Lettura **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Ottiene il titolo dell'asse. Solo lettura [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Specifica il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata a false e la proprietà IsUnderflowBin è true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la copia costruttiva delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la copia costruttiva delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Rappresenta il tipo di aggregazione dell'asse di categoria (binning). Applicato alla categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Rappresenta se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non ai grafici 3-D. Scrivi **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Specifica l'unità di tempo più piccola rappresentata sull'asse delle date. Scrivi [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Specifica il tipo dell'asse di categoria. Scrivi [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Scrivi **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Scrivi [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Scrivi [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Determina se un asse ha un titolo visibile. Scrivi **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Indica se l'unità maggiore dell'asse è assegnata automaticamente. Scrivi **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Indica se il valore massimo è assegnato automaticamente. Scrivi **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Indica se l'unità minore dell'asse è assegnata automaticamente. Scrivi **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Indica se il valore minimo è assegnato automaticamente. Scrivi **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Specifica il valore automatico del bin di overflow. Se false: usare la proprietà OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Specifica il valore automatico della spaziatura delle etichette dei tic. Se false: usare la proprietà TickLabelSpacing. Scrivi **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Specifica il valore automatico della spaziatura dei segni di tic. Se false: usare la proprietà TickMarksSpacing. Scrivi **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Specifica il valore automatico del bin di underflow. Se false: usare la proprietà UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. Scrivi **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Indica se il formato è collegato ai dati di origine. Scrivi **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Specifica se il bin di overflow è applicato. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Scrivi **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Specifica se il bin di underflow è applicato. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Rappresenta se l'asse è visibile. Scrivi **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Specifica la distanza delle etichette dall'asse. Applicato agli assi di categoria o data. Il valore deve essere tra 0% e 1000%. Scrivi **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Rappresenta la base logaritmica. Il valore predefinito è 10. Scrivi **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Rappresenta il tipo di segno di tic maggiore per l'asse specificato. Scrivi [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Rappresenta le unità maggiori per l'asse di data o di valore. Scrivi **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Rappresenta la scala dell'unità maggiore per l'asse di data. Scrivi [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Rappresenta il valore massimo sull'asse dei valori. Scrivi **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Rappresenta il tipo di segno di tic minore per l'asse specificato. Scrivi [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Rappresenta le unità minori per l'asse di data o di valore. Scrivi **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Rappresenta la scala dell'unità maggiore per l'asse di data. Scrivi [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Rappresenta il valore minimo sull'asse dei valori. Scrivi **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Rappresenta la stringa di formato per le etichette [Axis](./). Scrivi [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata a false e la proprietà IsOverflowBin è true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Rappresenta la posizione dell'asse. Scrivi [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Rappresenta la posizione delle etichette dei segni di tic sull'asse specificato. Scrivi [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Rappresenta l'angolo di rotazione delle etichette dei tic. Scrivi **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Specifica quante etichette di tic saltare tra le etichette disegnate. Applicato agli assi di categoria o di serie. Scrivi **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Specifica quanti segni di tic devono essere saltati prima di disegnarne il successivo. Applicato agli assi di categoria o di serie. Scrivi **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Specifica il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata a false e la proprietà IsUnderflowBin è true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Imposta la proprietà IAxis::get(set)_CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IAxis](../iaxis/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)