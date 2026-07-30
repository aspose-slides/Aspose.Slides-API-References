---
title: ILegend
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le proprietà della legenda del grafico.
type: docs
weight: 1080
url: /it/aspose.slides.charts/ilegend/
---
## ILegend classe

Rappresenta le proprietà della legenda del grafico.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Specifica l'altezza reale dell'elemento del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Specifica la larghezza reale dell'elemento del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Specifica la parte superiore reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo [IChart::ValidateChartLayout](../ichart/validatechartlayout/) prima per ottenere i valori reali. Leggi **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Ottiene la parte superiore dell'elemento del grafico come frazione dell'altezza del grafico. **float** di sola lettura. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Restituisce il grafico. Di sola lettura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Ottiene le voci della legenda. Di sola lettura [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Ottiene le proprietà della voce della legenda corrispondente al punto dati nel grafico all'indice specificato. Nei casi di tipi di grafico: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, il punto dati è preso dalla prima serie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Restituisce il formato di una legenda. Di sola lettura [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Specifica l'altezza dell'elemento del grafico come frazione dell'altezza del grafico. Leggi **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Determina se altri elementi del grafico possono sovrapporsi alla legenda. Leggi **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Specifica la posizione della legenda su un grafico. I valori non-NaN delle proprietà X, Y, Width, Height sovrascrivono l'effetto di questa proprietà. Leggi [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Di sola lettura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Ottiene il lato destro dell'elemento del grafico come frazione della larghezza del grafico. **float** di sola lettura. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Restituisce la diapositiva base. Di sola lettura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Restituisce il formato del testo del grafico. Di sola lettura [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Specifica la larghezza dell'elemento del grafico come frazione della larghezza del grafico. Leggi **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Specifica la posizione x (sinistra) dell'elemento del grafico come frazione della larghezza del grafico. Leggi **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Specifica la parte superiore dell'elemento del grafico come frazione dell'altezza del grafico. Leggi **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Specifica l'altezza dell'elemento del grafico come frazione dell'altezza del grafico. Scrivi **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Determina se altri elementi del grafico possono sovrapporsi alla legenda. Scrivi **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Specifica la posizione della legenda su un grafico. I valori non-NaN delle proprietà X, Y, Width, Heigt sovrascrivono l'effetto di questa proprietà. Scrivi [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Specifica la larghezza dell'elemento del grafico come frazione della larghezza del grafico. Scrivi **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Specifica la posizione x (sinistra) dell'elemento del grafico come frazione della larghezza del grafico. Scrivi **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Specifica la parte superiore dell'elemento del grafico come frazione dell'altezza del grafico. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece di condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ILayoutable](../ilayoutable/)
* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Classe [IActualLayout](../iactuallayout/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)