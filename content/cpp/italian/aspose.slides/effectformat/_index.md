---
title: EffectFormat
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta le proprietà degli effetti della forma.
type: docs
weight: 846
url: /it/aspose.slides/effectformat/
---
## EffectFormat classe


Rappresenta le proprietà degli effetti della forma.

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | Disabilita l'effetto sfocatura. |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | Disabilita l'effetto riempimento sovrapposto. |
| void [DisableGlowEffect](./disablegloweffect/)() override | Disabilita l'effetto bagliore. |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | Disabilita l'ombreggiatura interna. |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | Disabilita l'ombreggiatura esterna. |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | Disabilita l'effetto ombra predefinita. |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | Disabilita l'effetto riflesso. |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | Disabilita l'effetto bordo morbido. |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | Abilita l'effetto riempimento sovrapposto. |
| void [EnableGlowEffect](./enablegloweffect/)() override | Abilita l'effetto bagliore. |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | Abilita l'ombreggiatura interna. |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | Abilita l'ombreggiatura esterna. |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | Abilita l'effetto ombre predefinite. |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | Abilita l'effetto riflesso. |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | Abilita l'effetto bordo morbido. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | Effetto sfocatura. Leggi [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | Effetto riempimento sovrapposto. Leggi [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | Effetto bagliore. Leggi [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | Ombra interna. Leggi [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | Restituisce true se tutti gli effetti sono disabilitati (come appena creato, oggetto predefinito [EffectFormat](./)). Sola lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | Ombra esterna. Leggi [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Sola lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Sola lettura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | Ombra predefinita. Leggi [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | Riflessione. Leggi [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | Bordo morbido. Leggi [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati di formattazione degli effetti effettivi con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco di dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie dei sottotipi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnamento. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie dei sottotipi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | Effetto sfocatura. Scrivi [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | Effetto riempimento sovrapposto. Scrivi [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | Effetto bagliore. Scrivi [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | Ombra interna. Scrivi [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | Ombra esterna. Scrivi [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | Ombra predefinita. Scrivi [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | Riflessione. Scrivi [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | Bordo morbido. Scrivi [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | Imposta l'effetto sfocatura. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello a un puntatore debole (anziché condiviso). Permette di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costrutta C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [IEffectFormat](../ieffectformat/)
* Spazio dei nomi [Aspose::Slides](../)
* Library [Aspose.Slides](../../)