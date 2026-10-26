---
title: IReflection
second_title: Aspose.Slides för C++ API-referens
description: Representerar en reflektionseffekt.
type: docs
weight: 937
url: /sv/aspose.slides.effects/ireflection/
---
## IReflection klass

Representerar en reflektionseffekt.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radie. Läs **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Riktning för reflektionen. Läs **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Avstånd för reflektionen. Läs **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Specificerar slutpositionen (längs alfagradiensrampen) för det avslutande alfavärdet (procent). Läs **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Slutlig reflektionstäthet. (procent). Läs **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Specificerar riktningen för att förskjuta reflektionen. (vinkel). Läs **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Rektangeljustering. Läs [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Anger om reflektionen ska rotera med formen om formen roteras. Läs **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Specificerar den horisontella skalningsfaktorn, negativ skalning orsakar en vändning. (procent) Läs **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Specificerar den vertikala skalningsfaktorn, negativ skalning orsakar en vändning. (procent) Läs **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Specificerar den horisontella skevhetsvinkeln. Läs **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Specificerar den vertikala skevhetsvinkeln. Läs **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Specificerar startpositionen (längs alfagradiensrampen) för startalfavärdet (procent). Läs **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Startande reflektionstäthet. (procent). Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Hämtar effektiv data med ärvda egenskaper tillämpade. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radie. Skriv **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Riktning för reflektionen. Skriv **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Avstånd för reflektionen. Skriv **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Specificerar slutpositionen (längs alfagradiensrampen) för det avslutande alfavärdet (procent). Skriv **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Slutlig reflektionstäthet. (procent). Skriv **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Specificerar riktningen för att förskjuta reflektionen. (vinkel). Skriv **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Rektangeljustering. Skriv [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Anger om reflektionen ska rotera med formen om formen roteras. Skriv **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Specificerar den horisontella skalningsfaktorn, negativ skalning orsakar en vändning. (procent) Skriv **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Specificerar den vertikala skalningsfaktorn, negativ skalning orsakar en vändning. (procent) Skriv **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Specificerar den horisontella skevhetsvinkeln. Skriv **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Specificerar den vertikala skevhetsvinkeln. Skriv **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Specificerar startpositionen (längs alfagradiensrampen) för startalfavärdet (procent). Skriv **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Startande reflektionstäthet. (procent). Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'th mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsuppslag enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [IImageTransformOperation](../iimagetransformoperation/)
* Klass [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namnrymd [Aspose::Slides::Effects](../)
* Bibliotek [Aspose.Slides](../../)