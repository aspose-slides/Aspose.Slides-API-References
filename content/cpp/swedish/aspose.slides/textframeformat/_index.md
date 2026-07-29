---
title: TextFrameFormat
second_title: Aspose.Slides för C++ API-referens
description: Innehåller TextFrames formatTextFrameFormatting egenskaper.
type: docs
weight: 5461
url: /sv/aspose.slides/textframeformat/
---
## TextFrameFormat klass


Innehåller [TextFrame](../textframe/)'s formatTextFrameFormatting egenskaper.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med angivet objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med hjälp av C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Returnerar vertikal ankaretext i en [TextFrame](../textframe/). Läs [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Returnerar textens autofit-läge. Läs [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Om [NullableBool::True](../nullablebool/) så ska texten centreras horisontellt i rutan. Läs [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Returnerar antal kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värdet 0 betyder odefinierat värde. Läs **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Returnerar avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast gälla när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Hämtar hållning av texten platt även om en 3-D-rotations-effekt har tillämpats. Läs **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Returnerar den nedre marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Returnerar den vänstra marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Returnerar den högra marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Returnerar den övre marginalen (punkter) i en [TextFrame](../textframe/). Läs **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objekt. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Anger anpassad rotation som tillämpas på texten inom den avgränsande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation summerat från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Läs **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Bestämmer textriktning. Det resulterande värdet av visuell textrotation summerat från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Läs [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Returnerar [ThreeDFormat](../threedformat/)-objektet som representerar 3D-effektegenskaper för en text. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Hämtar textombrytningsform. Läs [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** om texten är ombrytt vid [TextFrame](../textframe/)'s marginaler. Läs [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiv formateringsdata för textramen med ärvd egendom tillämpad. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog med C# [System.Object.GetType()](../../system/object/gettype/) anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog med C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog med C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Sätter vertikal ankaretext i en [TextFrame](../textframe/). Skriv [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Sätter textens autofit-läge. Skriv [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Om [NullableBool::True](../nullablebool/) så ska texten centreras horisontellt i rutan. Skriv [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Sätter antal kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värdet 0 betyder odefinierat värde. Skriv **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Sätter avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast gälla när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Skriv **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Sätter att texten hålls platt även om en 3-D-rotations-effekt har tillämpats. Skriv **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Sätter den nedre marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Sätter den vänstra marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Sätter den högra marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Sätter den övre marginalen (punkter) i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Anger anpassad rotation som tillämpas på texten inom den avgränsande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation summerat från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Skriv **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Bestämmer textriktning. Det resulterande värdet av visuell textrotation summerat från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Skriv [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Sätter textombrytningsform. Skriv [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** om texten är ombrytt vid [TextFrame](../textframe/)'s marginaler. Skriv [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templatargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [TextFrameFormat](./textframeformat/)() | Initierar en ny instans av [TextFrameFormat](./) klass. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog med C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/)) konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [PVIObject](../pviobject/)
* Klass [ITextFrameFormat](../itextframeformat/)
* Klass [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)