---
title: IAutoShapeLock
second_title: Riferimento API di Aspose.Slides per C++
description: Determina quali operazioni sono disabilitate sul genitore AutoshapeEx.
type: docs
weight: 1379
url: /it/aspose.slides/iautoshapelock/
---
## classe IAutoShapeLock


Determina quali operazioni sono disabilitate sul genitore AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Determina se la modifica dei valori di aggiustamento è proibita. Legge **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Determina se la modifica delle punte di freccia è proibita. Legge **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Determina se una forma deve preservare il rapporto d'aspetto durante il ridimensionamento. Legge **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Determina se la modifica diretta del contorno di questa forma è proibita. Legge **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Determina se aggiungere questa forma a un gruppo è proibito. Legge **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Restituisce true se tutti i flag di blocco sono disabilitati. **bool** di sola lettura. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Determina se lo spostamento di questa forma è proibito. Legge **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Determina se la modifica dell'angolo di rotazione di questa forma è proibita. Legge **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Determina se la selezione di questa forma è proibita. Legge **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Determina se la modifica del tipo di forma è proibita. Legge **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Determina se il ridimensionamento di questa forma è proibito. Legge **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Determina se la modifica del testo è proibita. Legge **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Determina se la modifica dei valori di aggiustamento è proibita. Scrive **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Determina se la modifica delle punte di freccia è proibita. Scrive **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Determina se una forma deve preservare il rapporto d'aspetto durante il ridimensionamento. Scrive **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Determina se la modifica diretta del contorno di questa forma è proibita. Scrive **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Determina se aggiungere questa forma a un gruppo è proibito. Scrive **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Determina se lo spostamento di questa forma è proibito. Scrive **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Determina se la modifica dell'angolo di rotazione di questa forma è proibita. Scrive **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Determina se la selezione di questa forma è proibita. Scrive **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Determina se la modifica del tipo di forma è proibita. Scrive **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Determina se il ridimensionamento di questa forma è proibito. Scrive **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Determina se la modifica del testo è proibita. Scrive **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello come puntatore debole (invece di condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IBaseShapeLock](../ibaseshapelock/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)