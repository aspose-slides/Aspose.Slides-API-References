---
title: Trendline
second_title: Riferimento API di Aspose.Slides per C++
description: La classe rappresenta la linea di tendenza della serie del grafico
type: docs
weight: 1366
url: /it/aspose.slides.charts/trendline/
---
## Trendline classe

La classe rappresenta la linea di tendenza della serie del grafico

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inizializza TextFrameForOverriding con il testo nel parametro \"text\". Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **double** [get_Backward](./get_backward/)() override | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie in analisi. In grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Lettura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Restituisce il grafico padre. Solo lettura [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del valore Rsquaredvalue). Lettura **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Specifica che il valore R-squared della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). Lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Rappresenta il formato della linea di tendenza. Lettura [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie in analisi. In grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Lettura **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Specifica il valore in cui la linea di tendenza attraversa l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, lineare o polinomiale. Lettura **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Specifica l'ordine della linea di tendenza polinomiale. È ignorato per gli altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Lettura **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per le altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Lettura **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Rappresenta la voce della legenda relativa a questa linea di tendenza. Solo lettura [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Restituisce il formato del testo. Solo lettura [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Può contenere un testo riccamente formattato. Se questa proprietà non è nulla, il valore di testo formattato sovrascrive il testo auto-generato dell'etichetta dati. Il testo auto-generato dell'etichetta dati indica il testo gestito dalle proprietà ShowSeriesName, ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat. Solo lettura [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Ottiene il nome della linea di tendenza. Lettura [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Ottiene il tipo della linea di tendenza. Lettura [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_Backward](./set_backward/)(**double**) override | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie in analisi. In grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Scrivi **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del valore Rsquaredvalue). Scrivi **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Specifica che il valore R-squared della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). Scrivi **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Rappresenta il formato della linea di tendenza. Scrivi [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie in analisi. In grafici a dispersione e non a dispersione, il valore deve essere qualsiasi valore non negativo. Scrivi **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Specifica il valore in cui la linea di tendenza attraversa l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, lineare o polinomiale. Scrivi **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Specifica l'ordine della linea di tendenza polinomiale. È ignorato per gli altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Scrivi **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per le altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Scrivi **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Imposta il nome della linea di tendenza. Scrivi [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Imposta il tipo della linea di tendenza. Scrivi [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Imposta l'argomento template n-esimo come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare puntatori intelligenti o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare puntatori intelligenti o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare puntatori intelligenti o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare puntatori intelligenti o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [ITrendline](../itrendline/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)