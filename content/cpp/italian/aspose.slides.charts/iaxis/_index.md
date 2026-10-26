---
title: IAxis
second_title: Riferimento API di Aspose.Slides per C++
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
weight: 534
url: /it/aspose.slides.charts/iaxis/
---
## IAxis classe

Incapsula l'oggetto che rappresenta l'asse di un grafico.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Specifica l'unità maggiore reale dell'asse. Chiamare in precedenza il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Specifica la scala dell'unità maggiore reale dell'asse. Chiamare in precedenza il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Specifica il valore massimo reale sull'asse. Chiamare in precedenza il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Specifica l'unità minore reale dell'asse. Chiamare in precedenza il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Specifica la scala dell'unità minore reale dell'asse. Chiamare in precedenza il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Specifica il valore minimo reale sull'asse. Chiamare in precedenza il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) per ottenere il valore reale. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Rappresenta il tipo di aggregazione dell'asse di categoria (raggruppamento). Applicato alla categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Rappresenta se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non ai grafici 3-D. Leggi **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Specifica la più piccola unità di tempo rappresentata sull'asse della data. Leggi [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Specifica il tipo dell'asse di categoria. Leggi [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Restituisce il grafico. Solo lettura [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Leggi **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Leggi [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Leggi [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Rappresenta il formato dell'asse. Solo lettura [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Determina se un asse ha un titolo visibile. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indica se l'unità maggiore dell'asse è assegnata automaticamente. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indica se il valore massimo è assegnato automaticamente. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indica se l'unità minore dell'asse è assegnata automaticamente. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indica se il valore minimo è assegnato automaticamente. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Specifica il valore automatico del bin di overflow. Se false: utilizza la proprietà OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Specifica il valore automatico della spaziatura delle etichette dei tick. Se false: utilizza la proprietà TickLabelSpacing. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Specifica il valore automatico della spaziatura dei segni dei tick. Se false: utilizza la proprietà TickMarksSpacing. Leggi **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Specifica il valore automatico del bin di underflow. Se false: utilizza la proprietà UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. Leggi **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indica se il formato è dati sorgente collegati. Leggi **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Specifica se il bin di overflow è applicato. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Leggi **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Specifica se il bin di underflow è applicato. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Rappresenta se l'asse è visibile. Leggi **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Specifica la distanza delle etichette dall'asse. Applicato a un asse di categoria o data. Il valore deve essere tra 0% e 1000%. Leggi **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Rappresenta la base logaritmica. Il valore predefinito è 10. Leggi **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Rappresenta il formato delle linee di griglia principali su un asse del grafico. Solo lettura [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Rappresenta il tipo di segno di tick principale per l'asse specificato. Leggi [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Rappresenta le unità maggiori per l'asse della data o dei valori. Leggi **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Rappresenta la scala dell'unità maggiore per l'asse della data. Leggi [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Rappresenta il valore massimo sull'asse dei valori. Leggi **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Rappresenta il formato delle linee di griglia minori su un asse del grafico. Solo lettura [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Rappresenta il tipo di segno di tick minore per l'asse specificato. Leggi [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Rappresenta le unità minori per l'asse della data o dei valori. Leggi **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Rappresenta la scala dell'unità maggiore per l'asse della data. Leggi [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Rappresenta il valore minimo sull'asse dei valori. Leggi **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Rappresenta la stringa di formato per le etichette [Axis](../axis/). Leggi [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata a false e la proprietà IsOverflowBin è true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Rappresenta la posizione dell'asse. Leggi [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Rappresenta se le linee di griglia principali sono visualizzate. Solo lettura **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Rappresenta se le linee di griglia minori sono visualizzate. Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Restituisce la diapositiva base. Solo lettura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Restituisce il formato del testo del grafico. Solo lettura [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Rappresenta la posizione delle etichette dei segni di tick sull'asse specificato. Leggi [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Rappresenta l'angolo di rotazione delle etichette dei tick. Leggi **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Specifica quante etichette dei tick saltare tra le etichette disegnate. Leggi **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Specifica quanti segni dei tick devono essere saltati prima di disegnarne il successivo. Applicato a un asse di categoria o serie. Leggi **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Ottiene il titolo dell'asse. Solo lettura [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Specifica il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata a false e la proprietà IsUnderflowBin è true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la copia dei sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnamento. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la copia dei sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Rappresenta il tipo di aggregazione dell'asse di categoria (raggruppamento). Applicato alla categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Rappresenta se l'asse dei valori attraversa l'asse di categoria tra le categorie. Questa proprietà si applica solo agli assi di categoria e non ai grafici 3-D. Scrivi **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Specifica la più piccola unità di tempo rappresentata sull'asse della data. Scrivi [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Specifica il tipo dell'asse di categoria. Scrivi [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Scrivi **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Scrivi [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. Scrivi [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Determina se un asse ha un titolo visibile. Scrivi **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indica se l'unità maggiore dell'asse è assegnata automaticamente. Scrivi **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indica se il valore massimo è assegnato automaticamente. Scrivi **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indica se l'unità minore dell'asse è assegnata automaticamente. Scrivi **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indica se il valore minimo è assegnato automaticamente. Scrivi **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Specifica il valore automatico del bin di overflow. Se false: usa la proprietà OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Specifica il valore automatico della spaziatura delle etichette dei tick. Se false: usa la proprietà TickLabelSpacing. Scrivi **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Specifica il valore automatico della spaziatura dei segni dei tick. Se false: usa la proprietà TickMarksSpacing. Scrivi **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Specifica il valore automatico del bin di underflow. Se false: usa la proprietà UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. Scrivi **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indica se il formato è dati sorgente collegati. Scrivi **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Specifica se il bin di overflow è applicato. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Scrivi **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Specifica se il bin di underflow è applicato. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Rappresenta se l'asse è visibile. Scrivi **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Specifica la distanza delle etichette dall'asse. Applicato a un asse di categoria o data. Il valore deve essere tra 0% e 1000%. Scrivi **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Rappresenta la base logaritmica. Il valore predefinito è 10. Scrivi **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Rappresenta il tipo di segno di tick principale per l'asse specificato. Scrivi [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Rappresenta le unità maggiori per l'asse della data o dei valori. Scrivi **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Rappresenta la scala dell'unità maggiore per l'asse della data. Scrivi [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Rappresenta il valore massimo sull'asse dei valori. Scrivi **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Rappresenta il tipo di segno di tick minore per l'asse specificato. Scrivi [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Rappresenta le unità minori per l'asse della data o dei valori. Scrivi **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Rappresenta la scala dell'unità maggiore per l'asse della data. Scrivi [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Rappresenta il valore minimo sull'asse dei valori. Scrivi **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Rappresenta la stringa di formato per le etichette [Axis](../axis/). Scrivi [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato a [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Applicato agli assi di categoria. Utilizzato solo con le serie Histogram o HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Specifica il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata a false e la proprietà IsOverflowBin è true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Rappresenta la posizione dell'asse. Scrivi [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Rappresenta la posizione delle etichette dei segni di tick sull'asse specificato. Scrivi [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Rappresenta l'angolo di rotazione delle etichette dei tick. Scrivi **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Specifica quante etichette dei tick saltare tra le etichette disegnate. Scrivi **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Specifica quanti segni dei tick devono essere saltati prima di disegnarne il successivo. Applicato a un asse di categoria o serie. Scrivi **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Specifica il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata a false e la proprietà IsUnderflowBin è true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Imposta la proprietà IAxis::get(set)_CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)