---
title: EffectFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar effektegenskaper för en form.
type: docs
weight: 846
url: /sv/aspose.slides/effectformat/
---
## EffectFormat klass

Representerar effektegenskaper för en form.

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | Inaktiverar oskärpeeffekt. |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | Inaktiverar fyllningsövertäckningseffekt. |
| void [DisableGlowEffect](./disablegloweffect/)() override | Inaktiverar glow-effekt. |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | Inaktiverar inre skuggeffekt. |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | Inaktiverar yttre skuggeffekt. |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | Inaktiverar förinställd skuggeffekt. |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | Inaktiverar reflektionseffekt. |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | Inaktiverar mjuk kant-effekt. |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | Aktiverar fyllningsövertäckningseffekt. |
| void [EnableGlowEffect](./enablegloweffect/)() override | Aktiverar glow-effekt. |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | Aktiverar inre skuggeffekt. |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | Aktiverar yttre skuggeffekt. |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | Aktiverar förinställda skuggor-effekt. |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | Aktiverar reflektions-effekt. |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | Aktiverar mjuk kant-effekt. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil punkt-floating-jämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil dubbel-floating-jämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | Oskärpe-effekt. Läs [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | Fyllningsövertäckning-effekt. Läs [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | Glow-effekt. Läs [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | Inre skugga. Läs [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | Returnerar true om alla effekter är inaktiverade (som precis skapad, standard [EffectFormat](./)-objekt). Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | Yttre skugga. Läs [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objektet. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | Förinställd skugga. Läs [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | Reflektion. Läs [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | Mjuk kant. Läs [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontörens datastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiv effektformateringsdata med arv tillämpat. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hashkod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | Oskärpe-effekt. Skriv [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | Fyllningsövertäckning-effekt. Skriv [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | Glow-effekt. Skriv [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | Inre skugga. Skriv [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | Yttre skugga. Skriv [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | Förinställd skugga. Skriv [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | Reflektion. Skriv [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | Mjuk kant. Skriv [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | Ställer in oskärpe-effekt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [PVIObject](../pviobject/)
* Klass [IEffectFormat](../ieffectformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)