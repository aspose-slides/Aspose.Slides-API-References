---
title: ChartTitle
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le proprietà del titolo del grafico.
type: docs
weight: 326
url: /it/aspose.slides.charts/charttitle/
---
## Classe ChartTitle

Rappresenta le proprietà del titolo del grafico.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inizializza TextFrameForOverriding con il testo nel parametro \"text\". Se TextFrameForOverriding è già inizializzato, allora modifica semplicemente il suo testo. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specifica l'altezza reale dell'elemento del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specifica la larghezza reale dell'elemento del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specifica la posizione x reale (sinistra) dell'elemento del grafico relativa all'angolo superiore sinistro del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specifica la parte superiore reale dell'elemento del grafico relativa all'angolo superiore sinistro del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Inferiore. Solo lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Restituisce il grafico padre. Solo lettura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Restituisce gli stili di riempimento, linea ed effetto di un titolo. Solo lettura [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Restituisce l'altezza di un titolo come frazione dell'altezza del grafico. Leggi **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Determina se altri elementi del grafico possono sovrapporsi al titolo. Leggi **bool**. |
| **float** [get_Right](./get_right/)() override | Destra. Solo lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Restituisce il formato del testo. Solo lettura [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Può contenere un testo formattato riccamente. Se questa proprietà non è null, allora questo valore di testo formattato sovrascrive il testo generato automaticamente. Il testo generato automaticamente è una proprietà implicita dell'etichetta dei dati, dell'etichetta dell'unità di visualizzazione dell'asse dei valori, del titolo dell'asse, del titolo del grafico, dell'etichetta della linea di tendenza. Il testo generato automaticamente è formattato con la proprietà [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Solo lettura [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Restituisce la larghezza di un titolo come frazione della larghezza del grafico. Leggi **float**. |
| **float** [get_X](./get_x/)() override | Restituisce la coordinata x di un titolo come frazione della larghezza del grafico. Leggi **float**. |
| **float** [get_Y](./get_y/)() override | Restituisce la coordinata y di un titolo come frazione dell'altezza del grafico. Leggi **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il clonaggio di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_Height](./set_height/)(**float**) override | Imposta l'altezza di un titolo come frazione dell'altezza del grafico. Scrivi **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Determina se altri elementi del grafico possono sovrapporsi al titolo. Scrivi **bool**. |
| void [set_Width](./set_width/)(**float**) override | Imposta la larghezza di un titolo come frazione della larghezza del grafico. Scrivi **float**. |
| void [set_X](./set_x/)(**float**) override | Imposta la coordinata x di un titolo come frazione della larghezza del grafico. Scrivi **float**. |
| void [set_Y](./set_y/)(**float**) override | Imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IChartTitle](../icharttitle/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)