---
title: IConnectorLock
second_title: Riferimento API di Aspose.Slides per C++
description: Determina quali operazioni sono disattivate sul connettore genitore.
type: docs
weight: 1860
url: /it/aspose.slides/iconnectorlock/
---
## IConnectorLock classe

Determina quali operazioni sono disattivate sul genitore [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Determina se la modifica dei valori di aggiustamento è proibita. Lettura **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Determina se la modifica delle punte di freccia è proibita. Lettura **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Determina se una forma deve preservare il rapporto d'aspetto durante il ridimensionamento. Lettura **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Determina se la modifica diretta del contorno di questa forma è proibita. Lettura **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Determina se aggiungere questa forma a un gruppo è proibito. Lettura **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Restituisce true se tutti i flag di blocco sono disabilitati. Solo lettura **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Determina se lo spostamento di questa forma è proibito. Lettura **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Determina se la modifica dell'angolo di rotazione di questa forma è proibita. Lettura **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Determina se la selezione di questa forma è proibita. Lettura **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Determina se la modifica del tipo di forma è proibita. Lettura **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Determina se il ridimensionamento di questa forma è proibito. Lettura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnamento. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Determina se la modifica dei valori di aggiustamento è proibita. Scrittura **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Determina se la modifica delle punte di freccia è proibita. Scrittura **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Determina se una forma deve preservare il rapporto d'aspetto durante il ridimensionamento. Scrittura **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Determina se la modifica diretta del contorno di questa forma è proibita. Scrittura **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Determina se aggiungere questa forma a un gruppo è proibito. Scrittura **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Determina se lo spostamento di questa forma è proibito. Scrittura **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Determina se la modifica dell'angolo di rotazione di questa forma è proibita. Scrittura **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Determina se la selezione di questa forma è proibita. Scrittura **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Determina se la modifica del tipo di forma è proibita. Scrittura **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Determina se il ridimensionamento di questa forma è proibito. Scrittura **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IBaseShapeLock](../ibaseshapelock/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)