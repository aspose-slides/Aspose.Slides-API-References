---
title: ChartPlotArea
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il rettangolo in cui il grafico deve essere tracciato.
type: docs
weight: 248
url: /it/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea classe

Rappresenta il rettangolo in cui il grafico deve essere tracciato.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specifica l'altezza reale dell'elemento grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specifica la larghezza reale dell'elemento grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specifica la posizione x reale (sinistra) dell'elemento grafico rispetto all'angolo in alto a sinistra del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specifica la parte superiore reale dell'elemento grafico rispetto all'angolo in alto a sinistra del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Basso. Solo lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Solo lettura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Restituisce il formato di un'area di trama. Solo lettura [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Restituisce l'altezza di un riquadro di delimitazione dell'area di trama come frazione dell'altezza del grafico (da 0 a 1). Leggi **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Definisce come la posizione deve essere calcolata: true \\u2013 calcolata automaticamente; definita dalle proprietà X, Y, Width, Height. Solo lettura **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Se il layout dell'area di trama è definito manualmente, questa proprietà specifica se posizionare l'area di trama al suo interno (escludendo assi ed etichette) o all'esterno (includendo assi ed etichette). Leggi [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Destra. Solo lettura **float**. |
| **float** [get_Width](./get_width/)() override | Restituisce la larghezza di un riquadro di delimitazione dell'area di trama come frazione della larghezza del grafico (da 0 a 1). Leggi **float**. |
| **float** [get_X](./get_x/)() override | Restituisce la coordinata x dell'angolo in alto a sinistra del riquadro di delimitazione dell'area di trama come frazione della larghezza del grafico (da 0 a 1). Leggi **float**. |
| **float** [get_Y](./get_y/)() override | Restituisce la coordinata y dell'angolo in alto a sinistra del riquadro di delimitazione dell'area di trama come frazione dell'altezza del grafico (da 0 a 1). Leggi **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_Height](./set_height/)(**float**) override | Imposta l'altezza di un riquadro di delimitazione dell'area di trama come frazione dell'altezza del grafico (da 0 a 1). Scrivi **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Se il layout dell'area di trama è definito manualmente, questa proprietà specifica se posizionare l'area di trama al suo interno (escludendo assi ed etichette) o all'esterno (includendo assi ed etichette). Scrivi [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Imposta la larghezza di un riquadro di delimitazione dell'area di trama come frazione della larghezza del grafico (da 0 a 1). Scrivi **float**. |
| void [set_X](./set_x/)(**float**) override | Imposta la coordinata x dell'angolo in alto a sinistra del riquadro di delimitazione dell'area di trama come frazione della larghezza del grafico (da 0 a 1). Scrivi **float**. |
| void [set_Y](./set_y/)(**float**) override | Imposta la coordinata y dell'angolo in alto a sinistra del riquadro di delimitazione dell'area di trama come frazione dell'altezza del grafico (da 0 a 1). Scrivi **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Imposta il n-esimo argomento modello come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IChartPlotArea](../ichartplotarea/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)