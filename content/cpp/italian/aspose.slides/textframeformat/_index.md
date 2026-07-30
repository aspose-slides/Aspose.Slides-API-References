---
title: TextFrameFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene le proprietà formatTextFrameFormatting del TextFrame.
type: docs
weight: 5461
url: /it/aspose.slides/textframeformat/
---
## TextFrameFormat classe


Contiene le proprietà formatTextFrameFormatting di [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Restituisce il testo di ancoraggio verticale in un [TextFrame](../textframe/). Leggi [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Restituisce la modalità di adattamento automatico del testo. Leggi [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Se [NullableBool::True](../nullablebool/) allora il testo dovrebbe essere centrato orizzontalmente nella casella. Leggi [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Restituisce il numero di colonne nell'area di testo. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Il valore 0 indica valore non definito. Leggi **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Restituisce lo spazio tra le colonne di testo nell'area di testo (in punti). Questo dovrebbe essere applicato solo quando è presente più di 1 colonna. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Leggi **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Ottiene il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3-D. Leggi **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Restituisce il margine inferiore (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Restituisce il margine sinistro (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Restituisce il margine destro (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Restituisce il margine superiore (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Specifica la rotazione personalizzata applicata al testo all'interno della casella delimitatrice. Se non specificata, viene usata la rotazione della forma associata. Se specificata, questa viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Leggi **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Leggi [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Restituisce l'oggetto [ThreeDFormat](../threedformat/) che rappresenta le proprietà dell'effetto 3D per un testo. Solo lettura [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Ottiene la forma di adattamento del testo. Leggi [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** se il testo è avvolto ai margini di [TextFrame](../textframe/). Leggi [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati di formattazione effective del frame di testo con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiama direttamente o utilizza l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Imposta il testo di ancoraggio verticale in un [TextFrame](../textframe/). Scrivi [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Imposta la modalità di adattamento automatico del testo. Scrivi [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Se [NullableBool::True](../nullablebool/) allora il testo dovrebbe essere centrato orizzontalmente nella casella. Scrivi [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Imposta il numero di colonne nell'area di testo. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Il valore 0 indica valore non definito. Scrivi **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Imposta lo spazio tra le colonne di testo nell'area di testo (in punti). Questo dovrebbe essere applicato solo quando è presente più di 1 colonna. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Scrivi **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3-D. Scrivi **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Imposta il margine inferiore (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Imposta il margine sinistro (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Imposta il margine destro (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Imposta il margine superiore (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Specifica la rotazione personalizzata applicata al testo all'interno della casella delimitatrice. Se non specificata, viene usata la rotazione della forma associata. Se specificata, questa viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Scrivi [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Imposta la forma di adattamento del testo. Scrivi [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** se il testo è avvolto ai margini di [TextFrame](../textframe/). Scrivi [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | Inizializza una nuova istanza della classe [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiama direttamente o utilizza l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [ITextFrameFormat](../itextframeformat/)
* Classe [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)