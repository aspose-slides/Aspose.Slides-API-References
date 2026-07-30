---
title: IEffectFormat
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje vlastnosti efektů tvaru.
type: docs
weight: 2029
url: /cs/aspose.slides/ieffectformat/
---
## IEffectFormat třída

Reprezentuje vlastnosti efektů tvaru.

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | Zakazuje efekt rozostření. |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | Zakazuje efekt překrytí výplní. |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | Zakazuje efekt záře. |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | Zakazuje efekt vnitřního stínu. |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | Zakazuje efekt vnějšího stínu. |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | Zakazuje efekt přednastaveného stínu. |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | Zakazuje efekt odrazu. |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | Zakazuje efekt měkkého okraje. |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | Povolení efektu překrytí výplní. |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | Povolení efektu záře. |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | Povolení efektu vnitřního stínu. |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | Povolení efektu vnějšího stínu. |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | Povolení efektu přednastavených stínů. |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | Povolení efektu odrazu. |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | Povolení efektu měkkého okraje. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu v stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu v stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | Efekt rozostření. Číst [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Efekt překrytí výplní. Číst [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | Efekt záře. Číst [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Vnitřní stín. Číst [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Vrací true, pokud jsou všechny efekty zakázány (jako právě vytvořený výchozí objekt [EffectFormat](../effectformat/)). Pouze pro čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Vnější stín. Číst [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Přednastavený stín. Číst [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Odraz. Číst [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Měkký okraj. Číst [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | Získá data formátování efektu s aplikovaným děděním. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | Efekt rozostření. Zápis [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | Efekt překrytí výplní. Zápis [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | Efekt záře. Zápis [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | Vnitřní stín. Zápis [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | Vnější stín. Zápis [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | Přednastavený stín. Zápis [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | Odraz. Zápis [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | Měkký okraj. Zápis [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | Nastaví efekt rozostření. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako weak ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do režimu weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší weak čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží weak čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IEffectParamSource](../ieffectparamsource/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)