---
title: CompareInfo
second_title: Aspose.Slides för C++ API-referens
description: "Gör kultursensitiv strängjämförelse. Objekt av den här klassen bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 40
url: /sv/system.globalization/compareinfo/
---
## CompareInfo klass

Utför kultursensitiv strängjämförelse. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class CompareInfo : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Jämför strängar. Ej implementerad. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Jämför strängar. Endast Ordinal- och OrdinalIgnoreCase-lägen stöds. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Jämför en sektion av en sträng med en sektion av en andra sträng. Ej implementerad. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Jämför slutsektionen av en sträng med slutsektionen av en andra sträng med hjälp av strängjämförelsesmetoder. Ej implementerad. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Jämför slutsektionen av en sträng med slutsektionen av en andra sträng. Ej implementerad. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Jämför en sektion av en sträng med en sektion av en andra sträng med hjälp av strängjämförelsesmetoder. Ej implementerad. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | RTTI-information. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiterar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiterar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| int [get_LCID](./get_lcid/)() const | Hämtar LCID för kulturen som är associerad med jämförare. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Hämtar namn på kulturen som är associerad med jämförare. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Hämtar information om sorteringsversion. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Hämtar [CompareInfo](./) som är associerad med den angivna kulturen och använder strängjämförelsesmetoder i den angivna sammansättningen. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Hämtar [CompareInfo](./) som är associerad med den angivna kulturen och använder strängjämförelsesmetoder i den angivna sammansättningen. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Hämtar [CompareInfo](./) som är associerad med den angivna kulturen. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Hämtar [CompareInfo](./) som är associerad med den angivna kulturen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Hämtar strängens hashkod baserat på angivna jämförelsalternativ. |
| int [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Hämtar [SortKey](../sortkey/)-objekt för den angivna strängen med angivna jämförelsalternativ. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Hämtar [SortKey](../sortkey/)-objekt för den angivna strängen. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Söker efter delsträng. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Söker efter delsträng. Endast Ordinal-läge stöds. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Söker efter delsträng. Endast Ordinal-läge stöds. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Söker efter det angivna tecknet. Endast Ordinal-läge stöds. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Söker efter delsträng. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Söker efter det angivna tecknet. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Söker efter delsträng. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Söker efter det angivna tecknet. Endast Ordinal-läge stöds. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Söker efter det angivna tecknet. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Söker efter det angivna tecknet. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Söker efter delsträng. Endast Ordinal-läge stöds. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Söker efter det angivna tecknet. Endast Ordinal-läge stöds. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Kontrollerar om den angivna strängen börjar med det angivna prefixet med de angivna jämförelsalternativen. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Kontrollerar om den angivna strängen börjar med det angivna prefixet. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Kontrollerar om ett angivet tecken är sorteringsbart. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Kontrollerar om en angiven sträng är sorteringsbar. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Kontrollerar om den angivna strängen slutar med det angivna suffixet med de angivna jämförelsalternativen. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Kontrollerar om den angivna strängen slutar med det angivna suffixet. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Söker efter sista förekomsten av den angivna delsträngen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Söker efter sista förekomsten av den angivna delsträngen med de angivna jämförelsalternativen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Söker efter sista förekomsten av det angivna tecknet med de angivna jämförelsalternativen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Söker efter sista förekomsten av den angivna strängen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Söker efter sista förekomsten av den angivna strängen med de angivna jämförelsalternativen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Söker efter sista förekomsten av det angivna tecknet med de angivna jämförelsalternativen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Söker efter sista förekomsten av den angivna strängen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Söker efter sista förekomsten av det angivna tecknet. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Söker efter sista förekomsten av den angivna strängen med de angivna jämförelsalternativen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Söker efter sista förekomsten av det angivna tecknet med de angivna jämförelsalternativen. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Söker efter sista förekomsten av det angivna tecknet. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Söker efter sista förekomsten av det angivna tecknet. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiekonstruktör. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens på värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)