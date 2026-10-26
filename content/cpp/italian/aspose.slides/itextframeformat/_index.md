---
title: ITextFrameFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene le proprietà di formattazione del TextFrame.
type: docs
weight: 4083
url: /it/aspose.slides/itextframeformat/
---
## ITextFrameFormat classe

Contiene le proprietà di formattazione del [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, inclusi NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, inclusi NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Restituisce il testo di ancoraggio verticale in un [TextFrame](../textframe/). Leggi [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Restituisce la modalità di adattamento automatico del testo. Leggi [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Se [NullableBool::True](../nullablebool/) allora il testo dovrebbe essere centrato orizzontalmente nella casella. Leggi [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Restituisce il numero di colonne nell'area di testo. Questo valore deve essere un numero positivo. In caso contrario, il valore sarà impostato a zero. Il valore 0 indica un valore non definito. Leggi **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Restituisce lo spazio tra le colonne di testo nell'area di testo (in punti). Questo dovrebbe essere applicato solo quando è presente più di una colonna. Questo valore deve essere un numero positivo. In caso contrario, il valore sarà impostato a zero. Leggi **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Restituisce o imposta il mantenimento del testo fuori dalla scena 3D completamente. Leggi **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Restituisce il margine inferiore (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Restituisce il margine sinistro (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Restituisce il margine destro (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Restituisce il margine superiore (punti) in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. Se non specificata, viene usata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione aggiuntiva rispetto al testo. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Leggi **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Restituisce lo stile del testo. Solo lettura [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Leggi [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Restituisce l'oggetto [ThreeDFormat](../threedformat/) che rappresenta le proprietà dell'effetto 3D per un testo. Solo lettura [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Ottiene la forma di avvolgimento del testo. Leggi [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** se il testo è avvolto ai margini di [TextFrame](../textframe/). Leggi [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Ottiene i dati di formattazione effective del frame di testo con l'ereditarietà applicata. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Imposta il testo di ancoraggio verticale in un [TextFrame](../textframe/). Scrivi [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Imposta la modalità di adattamento automatico del testo. Scrivi [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Se [NullableBool::True](../nullablebool/) allora il testo dovrebbe essere centrato orizzontalmente nella casella. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Imposta il numero di colonne nell'area di testo. Questo valore deve essere un numero positivo. In caso contrario, il valore sarà impostato a zero. Il valore 0 indica un valore non definito. Scrivi **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Imposta lo spazio tra le colonne di testo nell'area di testo (in punti). Questo dovrebbe essere applicato solo quando è presente più di una colonna. Questo valore deve essere un numero positivo. In caso contrario, il valore sarà impostato a zero. Scrivi **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Restituisce o imposta il mantenimento del testo fuori dalla scena 3D completamente. Scrivi **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Imposta il margine inferiore (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Imposta il margine sinistro (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Imposta il margine destro (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Imposta il margine superiore (punti) in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. Se non specificata, viene usata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione aggiuntiva rispetto al testo. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Scrivi **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Scrivi [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Imposta la forma di avvolgimento del testo. Scrivi [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** se il testo è avvolto ai margini di [TextFrame](../textframe/). Scrivi [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore attuale del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)