---
title: IOuterShadow
second_title: Aspose.Slides för C++ API-referens
description: Representerar en yttre skuggeffekt.
type: docs
weight: 885
url: /sv/aspose.slides.effects/ioutershadow/
---
## IOuterShadow klass

Representerar en yttre skuggeffekt.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radie, i punkter. Standardvärde \\u2013 0 pt. Läs **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Riktning på skuggan, i grader. Standardvärde \\u2013 0 \\u00B0 (vänster-till-höger). Läs **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Avståndet för skuggan från objektet, i punkter. Standardvärde \\u2013 0 pt. Läs **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Rektangeljustering. Standardvärde \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Läs [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Indikerar om skuggan roterar tillsammans med formen. Standardvärde \\u2013 true. Läs **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Horisontell skalningsfaktor, i procent av den ursprungliga storleken. Negativ skalning ger en spegling. Standardvärde \\u2013 100 %. Läs **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Vertikal skalningsfaktor, i procent av den ursprungliga storleken. Negativ skalning ger en spegling. Standardvärde \\u2013 100 %. Läs **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Färg på skuggan. Standardvärde \\u2013 automatiskt svart (tema-beroende). Skrivskyddad [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Horisontell skevningsvinkel, i grader. Standardvärde \\u2013 0 \\u00B0. Läs **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Vertikal skevningsvinkel, i grader. Standardvärde \\u2013 0 \\u00B0. Läs **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Hämtar effektiv data med ärftlighet tillämpad. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fall med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fall med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radie, i punkter. Standardvärde \\u2013 0 pt. Skriv **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Riktning på skuggan, i grader. Standardvärde \\u2013 0 \\u00B0 (vänster-till-höger). Skriv **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Avståndet för skuggan från objektet, i punkter. Standardvärde \\u2013 0 pt. Skriv **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Rektangeljustering. Standardvärde \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Skriv [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Indikerar om skuggan roterar tillsammans med formen. Standardvärde \\u2013 true. Skriv **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Horisontell skalningsfaktor, i procent av den ursprungliga storleken. Negativ skalning ger en spegling. Standardvärde \\u2013 100 %. Skriv **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Vertikal skalningsfaktor, i procent av den ursprungliga storleken. Negativ skalning ger en spegling. Standardvärde \\u2013 100 %. Skriv **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Horisontell skevningsvinkel, i grader. Standardvärde \\u2013 0 \\u00B0. Skriv **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Vertikal skevningsvinkel, i grader. Standardvärde \\u2013 0 \\u00B0. Skriv **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [IImageTransformOperation](../iimagetransformoperation/)
* Klass [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namnrymd [Aspose::Slides::Effects](../)
* Bibliotek [Aspose.Slides](../../)