---
title: StringComparer
second_title: Aspose.Slides för C++ API-referens
description: "Jämför strängar med olika jämförelselägen. Objekt av den här klassen bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1288
url: /sv/system/stringcomparer/
---
## StringComparer klass

Jämför strängar med olika jämförelselägen. Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assert-fel. Omslut alltid denna klass i [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| int [Compare](./compare/)([args_type](./args_type/), [args_type](./args_type/)) const override | Jämför två strängar med aktuella inställningar. |
| static [StringComparerPtr](../stringcomparerptr/) [Create](./create/)(const [System::SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **bool**) | Skapar kulturspecifik jämförare. |
| **bool** [Equals](./equals/)([String](../string/), [String](../string/)) const override | Kontrollerar om två strängar är lika med de aktuella inställningarna. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCulture](./get_currentculture/)() | Singleton för aktuell kulturjämförare. |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Singleton för aktuell kulturjämförare utan skiftlägeskänslighet. |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCulture](./get_invariantculture/)() | Singleton för invariant kulturjämförare. |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Singleton för invariant kulturjämförare utan skiftlägeskänslighet. |
| static [StringComparerPtr](../stringcomparerptr/) [get_Ordinal](./get_ordinal/)() | Singleton för ordinaljämförare. |
| static [StringComparerPtr](../stringcomparerptr/) [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Singleton för ordinaljämförare utan skiftlägeskänslighet. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| int [GetHashCode](./gethashcode/)([String](../string/)) const override | Hämtar strängens hash-kod. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metod. Möjliggör hashning av egna objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metod. Möjliggör kloning av egna typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [RTTI_INFO_TEMPLATE_CLASS](../../system.collections.generic/iequalitycomparer/rtti_info_template_class/)([System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<T\>, System::BaseTypesInfo\<[System::Object](../object/)\>) | RTTI-information. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter n't:te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/)-metod. Möjliggör konvertering av egna objekt till sträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar upplåsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [args_type](./args_type/) | Argumenttyp. |

## Se även

* Klass [Object](../object/)
* Klass [IComparer](../../system.collections.generic/icomparer/)
* Klass [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)