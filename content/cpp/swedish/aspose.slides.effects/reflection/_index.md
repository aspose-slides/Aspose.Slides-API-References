---
title: Reflection
second_title: Aspose.Slides för C++ API-referens
description: Representerar en reflektions effekt.
type: docs
weight: 1067
url: /sv/aspose.slides.effects/reflection/
---
## Reflection klass

Representerar en [Reflection](./)-effekt.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Methods

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestämmer huruvida den angivna [Reflection](./) är lika med den aktuella [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius. Läs **double**. |
| **float** [get_Direction](./get_direction/)() override | Riktning för reflektion. Läs **float**. |
| **double** [get_Distance](./get_distance/)() override | Avstånd för reflektion. Läs **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Anger slutpositionen (längs den alfa-gradientrampen) för slutvärdet alfa (procent). Läs **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Slutreflektionsopacitet. (procent). Läs **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Anger riktningen för att förskjuta reflektionen. (vinkel). Läs **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rektangeljustering. Läs [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Anger huruvida reflektionen ska rotera med formen om formen roteras. Läs **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Anger den horisontella skalningsfaktorn, negativ skalning orsakar en spegling. (procent) Läs **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Anger den vertikala skalningsfaktorn, negativ skalning orsakar en spegling. (procent) Läs **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Anger den horisontella snedvinkeln. Läs **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Anger den vertikala snedvinkeln. Läs **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Anger startpositionen (längs den alfa-gradientrampen) för startvärdet alfa (procent). Läs **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Startreflektionsopacitet. (procent). Läs **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Skrivskyddad **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatstrukturen som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiv [Reflection](./)-effektdatas med ärftligheten tillämpad. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Fungerar som hash-funktion för en specifik typ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius. Skriv **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Riktning för reflektion. Skriv **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Avstånd för reflektion. Skriv **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Anger slutpositionen (längs den alfa-gradientrampen) för slutvärdet alfa (procent). Skriv **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Slutreflektionsopacitet. (procent). Skriv **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Anger riktningen för att förskjuta reflektionen. (vinkel). Skriv **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rektangeljustering. Skriv [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Anger huruvida reflektionen ska rotera med formen om formen roteras. Skriv **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Anger den horisontella skalningsfaktorn, negativ skalning orsakar en spegling. (procent) Skriv **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Anger den vertikala skalningsfaktorn, negativ skalning orsakar en spegling. (procent) Skriv **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Anger den horisontella snedvinkeln. Skriv **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Anger den vertikala snedvinkeln. Skriv **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Anger startpositionen (längs den alfa-gradientrampen) för startvärdet alfa (procent). Skriv **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Startreflektionsopacitet. (procent). Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [IReflection](../ireflection/)
* Klass [IVisualEffect](../ivisualeffect/)
* Klass [IPVIObject](../../aspose.slides/ipviobject/)
* Namnrymd [Aspose::Slides::Effects](../)
* Bibliotek [Aspose.Slides](../../)