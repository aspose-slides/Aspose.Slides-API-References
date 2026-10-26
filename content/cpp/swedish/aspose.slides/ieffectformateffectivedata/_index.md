---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides för C++ API-referens
description: Immutabelt objekt som innehåller effektiva egenskaper för effektformatering.
type: docs
weight: 2042
url: /sv/aspose.slides/ieffectformateffectivedata/
---
## IEffectFormatEffectiveData klass

Immutabelt objekt som innehåller effektiva formatinställningsegenskaper.

```cpp
class IEffectFormatEffectiveData : public Aspose::Slides::IEffectParamSource
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/)\> [get_BlurEffect](./get_blureffect/)() | Suddningseffekt. Skrivskyddad [Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Fyllnadsöverlagringseffekt. Skrivskyddad [Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/)\> [get_GlowEffect](./get_gloweffect/)() | Glöd-effekt. Skrivskyddad [Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Inre skugga. Skrivskyddad [Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Returnerar true om alla effekter är inaktiverade (som precis skapad, standard [EffectFormat](../effectformat/)-objekt). Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Yttre skugga. Skrivskyddad [Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Förinställd skugga. Skrivskyddad [Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Reflektion. Skrivskyddad [Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Mjuk kant. Skrivskyddad [Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatstruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av egna objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiskt typ av objekt. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av egna typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:e mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av egna objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning upp enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar

Detta gränssnitt används tillsammans med [IEffectFormat](../ieffectformat/)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.

## Se även

* Klass [IEffectParamSource](../ieffectparamsource/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)