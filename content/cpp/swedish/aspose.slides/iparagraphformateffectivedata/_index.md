---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides för C++ API-referens
description: Oföränderligt objekt som innehåller effektiva styckeformateringsegenskaper.
type: docs
weight: 3160
url: /sv/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData klass


Oföränderligt objekt som innehåller effektiva styckeformateringsegenskaper.

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
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
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Returnerar textjusteringen i ett stycke. Läs-endast [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | Returnerar ett punktformat för ett stycke. Läs-endast [IBulletFormatEffectiveData](../ibulletformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Returnerar standarddelformat för ett stycke. Läs-endast [IPortionFormatEffectiveData](../iportionformateffectivedata/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Returnerar standardtabulatorstorlek. Läs-endast **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Returnerar ett styckes djup. Läs-endast **int16_t**. |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Avgör om radbrytning för östasiatiska språk används i ett stycke. Läs-endast **bool**. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Returnerar en teckensnittjustering i ett stycke. Läs-endast [Slides::FontAlignment](../fontalignment/). |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | Avgör om hängande interpunktion används i ett stycke. Läs-endast **bool**. |
| virtual **float** [get_Indent](./get_indent/)() | Returnerar första rad-Indrag/hängande indrag för stycket. Hängande indrag kan definieras med negativa värden. Läs-endast **float**. |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | Avgör om latinisk radbrytning används i ett stycke. Läs-endast **bool**. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Returnerar vänstermarginalen i ett stycke. Läs-endast **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Returnerar högermarginalen i ett stycke. Läs-endast **float**. |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Avgör om skrivet från höger till vänster används i ett stycke. Läs-endast **bool**. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Returnerar mängden utrymme efter den sista raden i ett stycke. Läs-endast **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Returnerar mängden utrymme före den första raden i ett stycke. Läs-endast **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Returnerar mängden utrymme mellan baslinjer i ett stycke. Läs-endast **float**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | Returnerar tabulatorer för ett stycke. Läs-endast [ITabEffectiveData](../itabeffectivedata/)[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satset. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt nth-mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-satset. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar


Detta gränssnitt används tillsammans med [IParagraphFormat](../iparagraphformat/)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat. 

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)