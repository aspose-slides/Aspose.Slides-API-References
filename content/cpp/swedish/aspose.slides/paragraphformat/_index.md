---
title: ParagraphFormat
second_title: Aspose.Slides för C++ API-referens
description: Denna klass innehåller styckets formateringsegenskaper. Till skillnad från IParagraphFormatEffectiveData är alla egenskaper i denna klass skrivbara.
type: docs
weight: 4668
url: /sv/aspose.slides/paragraphformat/
---
## ParagraphFormat klass

Denna klass innehåller styckets formateringsegenskaper. Till skillnad från [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) är alla egenskaper i denna klass skrivbara.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Metoder

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Returnerar textjusteringen i ett stycke utan arv. Läs [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Returnerar standardtabulatorns storlek utan arv. Läs **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Determinerar om radbrytning för östasiatiskt språk används i ett stycke. Inget arv tillämpas. Läs [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Returnerar en teckensnittjustering i ett stycke utan arv. Läs [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Determinerar om hängande interpunktion används i ett stycke. Inget arv tillämpas. Läs [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Returnerar styckets första rad-indrag/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Determinerar om latinsk radbrytning används i ett stycke. Inget arv tillämpas. Läs [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Returnerar vänstermarginalen i ett stycke utan arv. Läs **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Returnerar högermarginalen i ett stycke utan arv. Läs **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objektet. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Determinerar om höger-till-vänster-skrivning används i ett stycke. Inget arv tillämpas. Läs [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Returnerar mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Returnerar mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Returnerar mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt - storlek i punkter. Inget arv tillämpas. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Returnerar tabulatorn i ett stycke på angivet index. Inget arv tillämpas. Skrivskyddad [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Returnerar tabulatorerna i ett stycke. Inget arv tillämpas. Skrivskyddad [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiv styckeformateringsdata med arv tillämpat. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [ParagraphFormat](./paragraphformat/)() | Initierar en ny instans av [ParagraphFormat](./)-klass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fall med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fall med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Ställer in textjusteringen i ett stycke utan arv. Skriv [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Ställer in standardtabulatorns storlek utan arv. Skriv **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Bestämmer om radbrytning för östasiatiskt språk används i ett stycke. Inget arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Ställer in teckensnittjustering i ett stycke utan arv. Skriv [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Bestämmer om hängande interpunktion används i ett stycke. Inget arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Ställer in styckets första rad-indrag/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Skriv **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Bestämmer om latinsk radbrytning används i ett stycke. Inget arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Ställer in vänstermarginalen i ett stycke utan arv. Skriv **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Ställer in högermarginalen i ett stycke utan arv. Skriv **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Bestämmer om höger-till-vänster-skrivning används i ett stycke. Inget arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Ställer in mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Skriv **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Ställer in mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Skriv **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Ställer in mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt - storlek i punkter. Inget arv tillämpas. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställ in n'te mallargument som en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för stycket som definierats för det specifika stycket. Det innebär att ingen arv tillämpas vid hämtning av värden, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formatparametervärdena inklusive ärvda måste du använda [ParagraphFormat::GetEffective](./geteffective/)-metoden som returnerar en [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-instans.

## Se även

* Klass [PVIObject](../pviobject/)
* Klass [IParagraphFormat](../iparagraphformat/)
* Klass [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)