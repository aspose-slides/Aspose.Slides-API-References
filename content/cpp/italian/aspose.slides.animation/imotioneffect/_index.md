---
title: IMotionEffect
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il comportamento dell'effetto di movimento.
type: docs
weight: 287
url: /it/aspose.slides.animation/imotioneffect/
---
## IMotionEffect classe

Rappresenta il comportamento dell'effetto di movimento.

```cpp
class IMotionEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | Rappresenta se i comportamenti di animazione sono accumulati. Leggi [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Leggi [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual **float** [get_Angle](./get_angle/)() | Descrive l'angolo relativo del percorso di movimento. Leggi **float**. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | Descrive il valore di offset relativo per l'animazione (in percentuali). Leggi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | Specifica una coordinata x/y da cui avviare l'animazione (in percentuali). Leggi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() | Specifica a cosa è relativo l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. Leggi [MotionOriginType](../motionorigintype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() | Specifica la primitiva del percorso seguita dalle coordinate per il movimento di animazione. Leggi [IMotionPath](../imotionpath/). |
| virtual [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() | Specifica come si muove il percorso di movimento quando la forma viene spostata. Leggi [MotionPathEditMode](../motionpatheditmode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | Rappresenta le proprietà del comportamento. Solo lettura [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() | Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X. Leggi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | Rappresenta le proprietà temporali per il comportamento dell'effetto. Leggi [ITiming](../itiming/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | Specifica la posizione target per un effetto di movimento di animazione (in percentuali). Leggi [System::Drawing::PointF](../../system.drawing/pointf/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamalo direttamente o utilizza l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia davvero nulla, si limita a inizializzare un nuovo oggetto e consente la copia costruita delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia davvero nulla, si limita a inizializzare un nuovo oggetto e consente la copia costruita delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | Rappresenta se i comportamenti di animazione sono accumulati. Scrivi [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | Rappresenta se il comportamento di animazione corrente è combinato con altre animazioni in esecuzione. Scrivi [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual void [set_Angle](./set_angle/)(**float**) | Descrive l'angolo relativo del percorso di movimento. Scrivi **float**. |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Descrive il valore di offset relativo per l'animazione (in percentuali). Scrivi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Specifica una coordinata x/y da cui avviare l'animazione (in percentuali). Scrivi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) | Specifica a cosa è relativo l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. Scrivi [MotionOriginType](../motionorigintype/). |
| virtual void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) | Specifica la primitiva del percorso seguita dalle coordinate per il movimento di animazione. Scrivi [IMotionPath](../imotionpath/). |
| virtual void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) | Specifica come si muove il percorso di movimento quando la forma viene spostata. Scrivi [MotionPathEditMode](../motionpatheditmode/). |
| virtual void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X. Scrivi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | Rappresenta le proprietà temporali per il comportamento dell'effetto. Scrivi [ITiming](../itiming/). |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Specifica la posizione target per un effetto di movimento di animazione (in percentuali). Scrivi [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo come puntatore debole (invece di condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamalo direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IBehavior](../ibehavior/)
* Spazio dei nomi [Aspose::Slides::Animation](../)
* Libreria [Aspose.Slides](../../)