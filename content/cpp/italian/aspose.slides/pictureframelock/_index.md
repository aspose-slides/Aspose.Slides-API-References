---
title: PictureFrameLock
second_title: Riferimento API Aspose.Slides per C++
description: Determina quali operazioni sono disabilitate sul genitore PictureFrame.
type: docs
weight: 4746
url: /it/aspose.slides/pictureframelock/
---
## PictureFrameLock classe


Determina quali operazioni sono disabilitate sul genitore [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Determina se la modifica dei valori di aggiustamento è vietata. Lettura **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Determina se la modifica delle punte delle frecce è vietata. Lettura **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Determina se una forma deve preservare il rapporto d'aspetto durante il ridimensionamento. Lettura **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Determina se il ritaglio di un'immagine è vietato. Lettura **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Determina se la modifica diretta del contorno di questa forma è vietata. Lettura **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Determina se l'aggiunta di questa forma a un gruppo è vietata. Lettura **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Restituisce true se tutti i flag di blocco sono disabilitati. Solo lettura **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Determina se lo spostamento di questa forma è vietato. Lettura **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Determina se la modifica dell'angolo di rotazione di questa forma è vietata. Lettura **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Determina se la selezione di questa forma è vietata. Lettura **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Determina se la modifica di un tipo di forma è vietata. Lettura **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Determina se il ridimensionamento di questa forma è vietato. Lettura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie nelle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento oggetti di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Determina se la modifica dei valori di aggiustamento è vietata. Scrittura **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Determina se la modifica delle punte delle frecce è vietata. Scrittura **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Determina se una forma deve preservare il rapporto d'aspetto durante il ridimensionamento. Scrittura **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Determina se il ritaglio di un'immagine è vietato. Scrittura **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Determina se la modifica diretta del contorno di questa forma è vietata. Scrittura **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Determina se l'aggiunta di questa forma a un gruppo è vietata. Scrittura **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Determina se lo spostamento di questa forma è vietato. Scrittura **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Determina se la modifica dell'angolo di rotazione di questa forma è vietata. Scrittura **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Determina se la selezione di questa forma è vietata. Scrittura **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Determina se la modifica di un tipo di forma è vietata. Scrittura **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Determina se il ridimensionamento di questa forma è vietato. Scrittura **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare puntatori intelligenti o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare puntatori intelligenti o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare puntatori intelligenti o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare puntatori intelligenti o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [BaseShapeLock](../baseshapelock/)
* Classe [IPictureFrameLock](../ipictureframelock/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)