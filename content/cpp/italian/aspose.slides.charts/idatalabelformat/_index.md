---
title: IDataLabelFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le opzioni di formattazione per DataLabel.
type: docs
weight: 963
url: /it/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat classe

Rappresenta le opzioni di formattazione per [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Restituisce il grafico. Solo lettura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Rappresenta il formato dell'etichetta dati. Solo lettura [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Leggi **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Rappresenta la stringa di formato per l'oggetto DataLabels. Leggi [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Rappresenta la posizione dell'etichetta dati. Leggi [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Imposta o restituisce una Variant che rappresenta il separatore utilizzato per le etichette dati su un grafico. Leggi [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False per nascondere. Leggi **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere. Leggi **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Determina se l'etichetta dati di un grafico specificato verrà visualizzata come richiamo dati o come etichetta dati. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Rappresenta il comportamento di visualizzazione del valore cellulare dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nascondere. Leggi **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False per nascondere. Leggi **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Rappresenta il comportamento di visualizzazione della chiave leggenda dell'etichetta dati di un grafico specificato. True se la chiave leggenda dell'etichetta dati è visibile. Leggi **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Leggi **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Restituisce un Booleano che indica il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nascondere. Leggi **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Leggi **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Restituisce la diapositiva base. Solo lettura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Restituisce il formato del testo del grafico. Solo lettura [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle subclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Scrivi **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Rappresenta la stringa di formato per l'oggetto DataLabels. Scrivi [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Rappresenta la posizione dell'etichetta dati. Scrivi [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Imposta o restituisce una Variant che rappresenta il separatore utilizzato per le etichette dati su un grafico. Scrivi [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False per nascondere. Scrivi **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere. Scrivi **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Determina se l'etichetta dati di un grafico specificato verrà visualizzata come richiamo dati o come etichetta dati. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Rappresenta il comportamento di visualizzazione del valore cellulare dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nascondere. Scrivi **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False per nascondere. Scrivi **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Rappresenta il comportamento di visualizzazione della chiave leggenda dell'etichetta dati di un grafico specificato. True se la chiave leggenda dell'etichetta dati è visibile. Scrivi **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Scrivi **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Imposta un Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nascondere. Scrivi **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nascondere. Scrivi **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento di modello a un puntatore debole (anziché condiviso). Consente di passare i puntatori in contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)