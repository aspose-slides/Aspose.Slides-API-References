---
title: LineFormat
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta il formato di una linea.
type: docs
weight: 4382
url: /it/aspose.slides/lineformat/
---
## LineFormat classe


Rappresenta il formato di una linea.

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | Determina se le due istanze di [LineFormat](./) sono uguali. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | Restituisce l'allineamento della linea. Leggi [LineAlignment](../linealignment/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | Restituisce la lunghezza della punta della freccia all'inizio di una linea. Leggi [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | Restituisce lo stile della punta della freccia all'inizio di una linea. Leggi [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | Restituisce la larghezza della punta della freccia all'inizio di una linea. Leggi [LineArrowheadWidth](../linearrowheadwidth/). |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | Restituisce lo stile di chiusura della linea. Leggi [LineCapStyle](../linecapstyle/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | Restituisce il modello di tratteggio personalizzato. Leggi **float**[]. |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | Restituisce lo stile di tratteggio della linea. Leggi [LineDashStyle](../linedashstyle/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | Restituisce la lunghezza della punta della freccia alla fine di una linea. Leggi [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | Restituisce lo stile della punta della freccia alla fine di una linea. Leggi [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | Restituisce la larghezza della punta della freccia alla fine di una linea. Leggi [LineArrowheadWidth](../linearrowheadwidth/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | Restituisce il formato di riempimento di una linea. Solo lettura [ILineFillFormat](../ilinefillformat/). |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | Restituisce true se il formato della linea non è definito (appena creato, predefinito). Solo lettura **bool**. |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | Restituisce lo stile di giunzione delle linee. Leggi [LineJoinStyle](../linejoinstyle/). |
| **float** [get_MiterLimit](./get_miterlimit/)() override | Restituisce il limite di spigolo di una linea. Leggi **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | Restituisce il formato schizzo di una linea. Solo lettura [ILineFillFormat](../ilinefillformat/). |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | Restituisce lo stile della linea. Leggi [LineStyle](../linestyle/). |
| **double** [get_Width](./get_width/)() override | Restituisce la larghezza di una linea. Leggi **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati di formattazione della linea effettivi con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata [System.Object.GetType()](../../system/object/gettype/) di C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore 'is' di C#. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo [Object.MemberwiseClone()](../../system/object/memberwiseclone/) di C#. Consente la clonazione dei tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | Imposta l'allineamento della linea. Scrivi [LineAlignment](../linealignment/). |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Imposta la lunghezza della punta della freccia all'inizio di una linea. Scrivi [LineArrowheadLength](../linearrowheadlength/). |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Imposta lo stile della punta della freccia all'inizio di una linea. Scrivi [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Imposta la larghezza della punta della freccia all'inizio di una linea. Scrivi [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | Imposta lo stile di chiusura della linea. Scrivi [LineCapStyle](../linecapstyle/). |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Imposta il modello di tratteggio personalizzato. Scrivi **float**[]. |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | Imposta lo stile di tratteggio della linea. Scrivi [LineDashStyle](../linedashstyle/). |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Imposta la lunghezza della punta della freccia alla fine di una linea. Scrivi [LineArrowheadLength](../linearrowheadlength/). |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Imposta lo stile della punta della freccia alla fine di una linea. Scrivi [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Imposta la larghezza della punta della freccia alla fine di una linea. Scrivi [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | Imposta lo stile di giunzione delle linee. Scrivi [LineJoinStyle](../linejoinstyle/). |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | Imposta il limite di spigolo di una linea. Scrivi **float**. |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | Imposta lo stile della linea. Scrivi [LineStyle](../linestyle/). |
| void [set_Width](./set_width/)(**double**) override | Imposta la larghezza di una linea. Scrivi **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento di template n-esimo come puntatore debole (invece di condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo [Object.ToString()](../../system/object/tostring/) di C#. Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [ILineFormat](../ilineformat/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)