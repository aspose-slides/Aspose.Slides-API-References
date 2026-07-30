---
title: ITrendline
second_title: Riferimento API di Aspose.Slides per C++
description: Classe che rappresenta la linea di tendenza della serie del grafico
type: docs
weight: 1223
url: /it/aspose.slides.charts/itrendline/
---
## ITrendline classe

La classe rappresenta la linea di tendenza della serie di un grafico

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inizializza TextFrameForOverriding con il testo nel parametro \"text\". Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **double** [get_Backward](./get_backward/)() | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima dei dati della serie in andamento. Su grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Leggi **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Restituisce il grafico. Solo lettura [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del Rsquaredvalue). Leggi **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Specifica che il valore R-quadrato della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). Leggi **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Rappresenta il formato della linea di tendenza. Leggi [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo i dati della serie in andamento. Su grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Leggi **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Leggi **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Specifica l'ordine della linea di tendenza polinomiale. È ignorato per altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Leggi **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Leggi **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Rappresenta la voce della legenda correlata a questa linea di tendenza. Solo lettura [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Restituisce la diapositiva base. Solo lettura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Restituisce il formato del testo del grafico. Solo lettura [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Può contenere un testo formattato riccamente. Se questa proprietà non è null, allora questo valore di testo formattato sovrascrive il testo generato automaticamente. Il testo generato automaticamente è una proprietà implicita dell'etichetta dei dati, dell'etichetta dell'unità di visualizzazione dell'asse dei valori, del titolo dell'asse, del titolo del grafico, dell'etichetta della linea di tendenza. Il testo generato automaticamente è formattato con la proprietà [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Solo lettura [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Ottiene il nome della linea di tendenza. Leggi [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Ottiene il tipo della linea di tendenza. Leggi [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dei dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza semplicemente un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_Backward](./set_backward/)(**double**) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima dei dati della serie in andamento. Su grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Scrivi **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del Rsquaredvalue). Scrivi **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Specifica che il valore R-quadrato della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). Scrivi **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Rappresenta il formato della linea di tendenza. Scrivi [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo i dati della serie in andamento. Su grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Scrivi **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Scrivi **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Specifica l'ordine della linea di tendenza polinomiale. È ignorato per altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Scrivi **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Scrivi **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Imposta il nome della linea di tendenza. Scrivi [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Imposta il tipo della linea di tendenza. Scrivi [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IOverridableText](../ioverridabletext/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)