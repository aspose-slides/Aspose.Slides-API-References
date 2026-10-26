---
title: IEffectFormatEffectiveData
second_title: Riferimento API di Aspose.Slides per C++
description: Oggetto immutabile che contiene le proprietà di formattazione dell'effetto effettivo.
type: docs
weight: 2042
url: /it/aspose.slides/ieffectformateffectivedata/
---
## IEffectFormatEffectiveData classe

Oggetto immutabile che contiene le proprietà di formattazione dell'effetto effettivo.

```cpp
class IEffectFormatEffectiveData : public Aspose::Slides::IEffectParamSource
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/)\> [get_BlurEffect](./get_blureffect/)() | Effetto sfocatura. Sola lettura [Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Effetto sovrapposizione riempimento. Sola lettura [Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/)\> [get_GlowEffect](./get_gloweffect/)() | Effetto bagliore. Sola lettura [Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Ombra interna. Sola lettura [Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Restituisce true se tutti gli effetti sono disabilitati (come un oggetto [EffectFormat](../effectformat/) appena creato, predefinito). Sola lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Ombra esterna. Sola lettura [Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Ombra predefinita. Sola lettura [Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Riflesso. Sola lettura [Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Bordo morbido. Sola lettura [Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement di C# per il blocco. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la copia costruttiva delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la copia costruttiva delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece di condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() statement di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Note

Questa interfaccia è usata insieme all'interfaccia [IEffectFormat](../ieffectformat/) per restituire i valori di formattazione effettiva con l'ereditarietà applicata.

## Vedi anche

* Classe [IEffectParamSource](../ieffectparamsource/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)