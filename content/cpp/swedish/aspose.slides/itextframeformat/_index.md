---
title: ITextFrameFormat
second_title: Aspose.Slides för C++ API-referens
description: Innehåller TextFrames formaterings egenskaper.
type: docs
weight: 4083
url: /sv/aspose.slides/itextframeformat/
---
## ITextFrameFormat klass

Contains the [TextFrame](../textframe/)'s formatting properties.

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Returnerar vertikal ankaretext i en [TextFrame](../textframe/). Läs [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Returnerar textens autofit-läge. Läs [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Om [NullableBool::True](../nullablebool/) bör texten centrerad i rutan horisontellt. Läs [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Returnerar antalet kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värde 0 betyder odefinierat värde. Läs **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Returnerar avståndet mellan textkolumner i textområdet (i punkter). Detta gäller endast när mer än 1 kolumn är närvarande. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Returnerar eller ställer in att hålla texten helt ute ur 3D-scenen. Läs **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Returnerar den nedre marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Returnerar den vänstra marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Returnerar den högra marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Returnerar den övre marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Specificerar den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation summeras från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Returnerar textens stil. Skrivskyddad [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Bestämmer textorientering. Läs [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Returnerar [ThreeDFormat](../threedformat/)-objektet som representerar 3D-effektegenskaper för en text. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Hämtar textens omslagningsform. Läs [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **Sant** om texten är omsluten vid [TextFrame](../textframe/)-marginaler. Läs [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Hämtar effektiv formateringsdata för textramen med ärvd egenskaper tillämpade. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C#-metoden [Object.GetHashCode()](../../system/object/gethashcode/). Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C#-anropet [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C#-satsen lock() för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C#-metoden [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Ställer in vertikal ankaretext i en [TextFrame](../textframe/). Skriv [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Ställer in textens autofit-läge. Skriv [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Om [NullableBool::True](../nullablebool/) bör texten centrerad i rutan horisontellt. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Ställer in antalet kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värde 0 betyder odefinierat värde. Skriv **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Ställer in avståndet mellan textkolumner i textområdet (i punkter). Detta gäller endast när mer än 1 kolumn är närvarande. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Skriv **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Returnerar eller ställer in att hålla texten helt ute ur 3D-scenen. Skriv **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ställer in den nedre marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ställer in den vänstra marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ställer in den högra marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ställer in den övre marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Specificerar den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation summeras från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Skriv **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Bestämmer textorientering. Skriv [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Ställer in textens omslagningsform. Skriv [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **Sant** om texten är omsluten vid [TextFrame](../textframe/)-marginaler. Skriv [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar C#-satsen lock() för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i ställe smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i ställe smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)