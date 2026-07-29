---
title: IParagraphFormat
second_title: Aspose.Slides för C++ API-referens
description: Denna klass innehåller styckeformateringsegenskaperna. Till skillnad från IParagraphFormatEffectiveData är alla egenskaper i den här klassen skrivbara.
type: docs
weight: 3147
url: /sv/aspose.slides/iparagraphformat/
---
## IParagraphFormat klass


Den här klassen innehåller styckeformateringsegenskaperna. Till skillnad från [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) är alla egenskaper i den här klassen skrivbara.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Returnerar textjusteringen i ett stycke utan arv. Läs [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Returnerar punktlistformatet för stycket. Skrivskyddad [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Returnerar standarddelformat för ett stycke. Ingen arv tillämpas. Skrivskyddad [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Returnerar standardflikstorlek utan arv. Läs **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Returnerar djupet på stycket. Värdet 0 betyder odefinierat värde. Läs **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Fastställer om radbrytning för östasiatiska språk används i ett stycke. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Returnerar en teckensnittjustering i ett stycke utan arv. Läs [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Fastställer om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Returnerar styckets första radindragning/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Fastställer om latinsk radbrytning används i ett stycke. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Returnerar vänstermarginalen i ett stycke utan arv. Läs **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Returnerar högermarginalen i ett stycke utan arv. Läs **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Fastställer om höger-till-vänster-skrivning används i ett stycke. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Returnerar mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som blankrummet ska vara. Ett negativt värde anger storleken på blankrummet i punktstorlek. Läs **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Returnerar mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som blankrummet ska vara. Ett negativt värde anger storleken på blankrummet i punktstorlek. Läs **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Returnerar mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Returnerar fliken för ett stycke på angivet index. Ingen arv tillämpas. Skrivskyddad [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Returnerar flikar för ett stycke. Ingen arv tillämpas. Skrivskyddad [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Hämtar effektiv styckeformateringsdata med arv tillämpat. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr med referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Ställer in textjusteringen i ett stycke utan arv. Skriv [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Ställer in standardflikstorlek utan arv. Skriv **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Ställer in styckets djup. Värdet 0 betyder odefinierat värde. Skriv **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Fastställer om radbrytning för östasiatiska språk används i ett stycke. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Ställer in en teckensnittjustering i ett stycke utan arv. Skriv [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Fastställer om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Ställer in styckets första radindragning/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Skriv **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Fastställer om latinsk radbrytning används i ett stycke. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Ställer in vänstermarginalen i ett stycke utan arv. Skriv **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Ställer in högermarginalen i ett stycke utan arv. Skriv **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Fastställer om höger-till-vänster-skrivning används i ett stycke. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Ställer in mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som blankrummet ska vara. Ett negativt värde anger storleken på blankrummet i punktstorlek. Skriv **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Ställer in mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procentandelen av teckensnittsstorleken som blankrummet ska vara. Ett negativt värde anger storleken på blankrummet i punktstorlek. Skriv **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Ställer in mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar


Denna klass används för att returnera och manipulera styckeformateringsegenskaper som definieras för det specifika stycket. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierad".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [IParagraphFormat::GetEffective](./geteffective/)-metoden som returnerar en [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-instans.

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)