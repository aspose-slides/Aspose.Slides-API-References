---
title: DataLabelFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le opzioni di formattazione per DataLabel.
type: docs
weight: 391
url: /it/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat classe

Rappresenta le opzioni di formattazione per [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Restituisce il grafico. Sola lettura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Rappresenta il formato dell'etichetta dati. Sola lettura [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Solo lettura **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Rappresenta la stringa di formato per l'oggetto DataLabels. Lettura [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Sola lettura [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Sola lettura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Rappresenta la posizione dell'etichetta dati. Lettura [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. Lettura [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False per nascondere. Sola lettura **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere. Sola lettura **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Determina se l'etichetta dati di un grafico specificato verrà visualizzata come richiamo dati o come etichetta dati. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nascondere. Sola lettura **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False per nascondere. Sola lettura **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Rappresenta il comportamento di visualizzazione della chiave legenda dell'etichetta dati di un grafico specificato. True se la chiave legenda dell'etichetta dati è visibile. Sola lettura **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Sola lettura **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Restituisce un Booleano che indica il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nascondere. Sola lettura **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Sola lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Restituisce il formato testo del grafico. Sola lettura [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso di un valore specificato. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Scrive **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Rappresenta la stringa di formato per l'oggetto DataLabels. Scrivi [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Rappresenta la posizione dell'etichetta dati. Scrivi [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. Scrivi [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False per nascondere. Scrivi **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere. Scrivi **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Determina se l'etichetta dati di un grafico specificato verrà visualizzata come richiamo dati o come etichetta dati. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nascondere. Scrivi **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False per nascondere. Scrivi **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Rappresenta il comportamento di visualizzazione della chiave legenda dell'etichetta dati di un grafico specificato. True se la chiave legenda dell'etichetta dati è visibile. Scrivi **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Scrivi **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Imposta un Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nascondere. Scrivi **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Scrivi **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PVIObject](../../aspose.slides/pviobject/)
* Classe [IDataLabelFormat](../idatalabelformat/)
* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)