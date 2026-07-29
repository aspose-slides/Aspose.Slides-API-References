---
title: Match
second_title: Aspose.Slides för C++ API-referens
description: "Enstaka matchning av reguljärt uttryck över en sträng. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omge alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 66
url: /sv/system.text.regularexpressions/match/
---
## Match-klass


[Single](../../system/single/) matchning av reguljärt uttryck över en sträng. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omge alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Match : public System::Text::RegularExpressions::Group
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AddCapture](./addcapture/)(const [CapturePtr](../captureptr/)\&) | Lägger till en fångst i matchen. |
| void [AddGroup](./addgroup/)(const [GroupPtr](../groupptr/)\&) | Lägger till en grupp i matchen. |
| [Capture](../capture/capture/)(const [UStringPtr](../ustringptr/)\&, int, int) | Konstruktör. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [CaptureCollectionPtr](../capturecollectionptr/) [get_Captures](../group/get_captures/)() | Hämtar tillgängliga fångster. |
| static [MatchPtr](../matchptr/) [get_Empty](./get_empty/)() | Åtkomst till tom match. |
| [GroupCollectionPtr](../groupcollectionptr/) [get_Groups](./get_groups/)() | Hämtar grupplista. |
| int [get_Index](../capture/get_index/)() const | Hämtar index för fångad delsträng. |
| int [get_Length](../capture/get_length/)() const | Hämtar längden på den fångade delsträngen. |
| **bool** [get_Success](../group/get_success/)() | Kontrollerar om fångst var lyckad för denna grupp. |
| [String](../../system/string/) [get_Value](../capture/get_value/)() const | Hämtar fångad delsträng. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [Group](../group/group/)(const [UStringPtr](../ustringptr/)\&, int, int) | Konstruktör. |
| [Group](../group/group/)() | Konstruktör för tom grupp. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropas direkt eller via [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| [Match](./match/)(const [UStringPtr](../ustringptr/)\&, int, int) | Konstruktör. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [MatchPtr](../matchptr/) [NextMatch](./nextmatch/)() | Iterering över matchningar. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual [String](../../system/string/) [Result](./result/)(const [String](../../system/string/)\&) | Formaterar sträng genom att ersätta delmatchningsreferenser med deras värden. |
| void [SetMappedIndexes](./setmappedindexes/)(const std::vector\<int\>\&) |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToString](../capture/tostring/)() const override | Hämtar fångad delsträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropas direkt eller via [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [Group](../group/)
* Namnrymd [System::Text::RegularExpressions](../)
* Bibliotek [Aspose.Slides](../../)