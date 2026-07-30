---
title: DataLabel
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le etichette di una serie.
type: docs
weight: 365
url: /it/aspose.slides.charts/datalabel/
---
## DataLabel classe

Rappresenta le etichette di una serie.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inizializza TextFrameForOverriding con il testo nel parametro \"text\". Se TextFrameForOverriding è già stato inizializzato, allora ne modifica semplicemente il testo. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Crea una nuova istanza della classe [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specifica l'altezza reale dell'elemento del grafico. Chiama il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specifica la larghezza reale dell'elemento del grafico. Chiama il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiama il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specifica la parte superiore reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiama il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Fondo. Solo lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Restituisce il grafico padre. Solo lettura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Restituisce il formato dell'etichetta dati. Solo lettura [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Restituisce l'altezza di un titolo come frazione dell'altezza del grafico. Leggi **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False indica che l'etichetta dati non è visibile (e quindi tutti i flag Show* (ShowValue, ...) sono false). Solo lettura **bool**. |
| **float** [get_Right](./get_right/)() override | Destra. Solo lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Restituisce il formato del testo. Solo lettura [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Può contenere un testo ricco formattato. Se questa proprietà non è nulla, allora questo valore di testo formattato sovrascrive il testo auto-generato dell'etichetta dati. Il testo auto-generato dell'etichetta dati è il testo gestito dalle proprietà ShowSeriesName, ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat. Solo lettura [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Ottiene la cella di dati del workbook. Applicato se la proprietà IDataLabelFormat::get(set)_ShowLabelValueFromCell è true. |
| **float** [get_Width](./get_width/)() override | Restituisce la larghezza di un titolo come frazione della larghezza del grafico. Leggi **float**. |
| **float** [get_X](./get_x/)() override | Restituisce la coordinata x di un titolo come frazione della larghezza del grafico. Leggi **float**. |
| **float** [get_Y](./get_y/)() override | Restituisce la coordinata y di un titolo come frazione dell'altezza del grafico. Leggi **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Restituisce il testo reale dell'etichetta basato sulle impostazioni [DataLabelFormat](../datalabelformat/) o sul valore [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | Rende l'etichetta dati nascosta impostando tutti i flag Show* (ShowValue, ...) allo stato false. IsVisible sarà false dopo questo. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiama direttamente o utilizza l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e a consentire la costruzione di copie nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e a consentire la costruzione di copie nelle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_Height](./set_height/)(**float**) override | Imposta l'altezza di un titolo come frazione dell'altezza del grafico. Scrivi **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Imposta la cella di dati del workbook. Applicato se la proprietà IDataLabelFormat::get(set)_ShowLabelValueFromCell è true. |
| void [set_Width](./set_width/)(**float**) override | Imposta la larghezza di un titolo come frazione della larghezza del grafico. Scrivi **float**. |
| void [set_X](./set_x/)(**float**) override | Imposta la coordinata x di un titolo come frazione della larghezza del grafico. Scrivi **float**. |
| void [set_Y](./set_y/)(**float**) override | Imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiama direttamente o utilizza l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IDataLabel](../idatalabel/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)