---
title: ITextFrameFormatEffectiveData
second_title: Riferimento API di Aspose.Slides per C++
description: Oggetto immutabile che contiene le proprietà di formattazione effettiva del frame di testo.
type: docs
weight: 4096
url: /it/aspose.slides/itextframeformateffectivedata/
---
## ITextFrameFormatEffectiveData classe

Oggetto immutabile che contiene le proprietà di formattazione effettiva del frame di testo.

```cpp
class ITextFrameFormatEffectiveData : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Restituisce il testo di ancoraggio verticale in un [TextFrame](../textframe/). Sola lettura [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Restituisce la modalità di adattamento automatico del testo. Sola lettura [TextAutofitType](../textautofittype/). |
| virtual **bool** [get_CenterText](./get_centertext/)() | Restituisce se il testo deve essere centrato orizzontalmente nella casella. Sola lettura **bool**. |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Specifica il numero di colonne di testo nel rettangolo di delimitazione. Sola lettura **int32_t**. |
| virtual **float** [get_ColumnSpacing](./get_columnspacing/)() | Specifica lo spazio tra le colonne di testo nell'area di testo (in punti). Sola lettura **float**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Restituisce il margine inferiore (punti) in un [TextFrame](../textframe/). Sola lettura **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Restituisce il margine sinistro (punti) in un [TextFrame](../textframe/). Sola lettura **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Restituisce il margine destro (punti) in un [TextFrame](../textframe/). Sola lettura **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Restituisce il margine superiore (punti) in un [TextFrame](../textframe/). Sola lettura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyleEffectiveData](../itextstyleeffectivedata/)\> [get_TextStyle](./get_textstyle/)() | Restituisce lo stile del testo effettivo. Sola lettura [ITextStyleEffectiveData](../itextstyleeffectivedata/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Restituisce l'orientazione del testo. Sola lettura [Slides::TextVerticalType](../textverticaltype/). |
| virtual **bool** [get_WrapText](./get_wraptext/)() | Restituisce se il testo è interrotto ai margini di [TextFrame](../textframe/). Sola lettura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, inizializza solo un nuovo oggetto e consente la costruzione tramite copia delle subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, inizializza solo un nuovo oggetto e consente la costruzione tramite copia delle subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Osservazioni

Questa interfaccia è utilizzata insieme all'interfaccia [ITextFrameFormat](../itextframeformat/) per restituire i valori di formattazione effettiva con l'ereditarietà applicata. 

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)