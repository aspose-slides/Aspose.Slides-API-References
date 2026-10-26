---
title: OuterShadow
second_title: Aspose.Slides för C++ API-referens
description: Representerar en Outer Shadow-effekt.
type: docs
weight: 1041
url: /sv/aspose.slides.effects/outershadow/
---
## OuterShadow klass

Representerar en Outer Shadow-effekt.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Avgör om den angivna [OuterShadow](./) är lika med den aktuella [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radie, i punkter. Standardvärde – 0 pt. Läs **double**. |
| **float** [get_Direction](./get_direction/)() override | Riktning för skuggan, i grader. Standardvärde – 0 ° (vänster-till-höger). Läs **float**. |
| **double** [get_Distance](./get_distance/)() override | Avståndet för skuggan från objektet, i punkter. Standardvärde – 0 pt. Läs **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rektangeljustering. Standardvärde – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Läs [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Indikerar om skuggan roterar tillsammans med formen. Standardvärde – true. Läs **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Horisontell skalningsfaktor, i procent av originalstorleken. Negativ skalning orsakar en spegling. Standardvärde – 100 %. Läs **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Vertikal skalningsfaktor, i procent av originalstorleken. Negativ skalning orsakar en spegling. Standardvärde – 100 %. Läs **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Färgen på skuggan. Standardvärde – automatiskt svart (tema-beroende). Skrivskyddad [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Horisontell skevvinkel, i grader. Standardvärde – 0 °. Läs **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Vertikal skevvinkel, i grader. Standardvärde – 0 °. Läs **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Skrivskyddad **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiv Outer Shadow-effektsdata med ärftlighet tillämpad. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Fungerar som en hash-funktion för en viss typ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radie, i punkter. Standardvärde – 0 pt. Skriv **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Riktning för skuggan, i grader. Standardvärde – 0 ° (vänster-till-höger). Skriv **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Avståndet för skuggan från objektet, i punkter. Standardvärde – 0 pt. Skriv **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rektangeljustering. Standardvärde – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Skriv [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Indikerar om skuggan roterar tillsammans med formen. Standardvärde – true. Skriv **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Horisontell skalningsfaktor, i procent av originalstorleken. Negativ skalning orsakar en spegling. Standardvärde – 100 %. Skriv **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Vertikal skalningsfaktor, i procent av originalstorleken. Negativ skalning orsakar en spegling. Standardvärde – 100 %. Skriv **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Horisontell skevvinkel, i grader. Standardvärde – 0 °. Skriv **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Vertikal skevvinkel, i grader. Standardvärde – 0 °. Skriv **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector alternativt. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [IOuterShadow](../ioutershadow/)
* Klass [IVisualEffect](../ivisualeffect/)
* Klass [IPVIObject](../../aspose.slides/ipviobject/)
* Namnrymd [Aspose::Slides::Effects](../)
* Bibliotek [Aspose.Slides](../../)