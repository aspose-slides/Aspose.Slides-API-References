---
title: NumberFormatInfo
second_title: Aspose.Slides för C++ API-referens
description: "Håller information om hur man formaterar tal. Setter operationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av den här klassen bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 248
url: /sv/system.globalization/numberformatinfo/
---
## NumberFormatInfo klass

Håller information om hur man formaterar tal. Setter-operationer är endast aktiverade på icke-read-only-objekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonar formatinformation. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flotpunktjämförelse i C#-stil där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar dubbelprecisionjämförelse i C#-stil där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Hämtar antalet decimaler för valuta. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Hämtar valutans decimalavgränsare. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Hämtar valutans gruppavgränsare. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Hämtar antal decimaler per grupp för valuta. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Hämtar valutans negativa mönster. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Hämtar valutans positiva mönster. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Hämtar valutasymbol. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Hämtar aktuellt trådkulturspecificerat formatinformation för nummer. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Hämtar ett värde som anger hur siffrors form ska visas. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Hämtar invariant kulturspecificerat formatinformation för nummer. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om formatet är skrivskyddat. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Hämtar Not-a-Number-symbolen. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Hämtar siffersymboler (0 till 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Hämtar negativ oändlighetssymbol. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Hämtar negativt tecken. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Hämtar antal decimaler. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Hämtar decimalavgränsare. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Hämtar talgruppavgränsare. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Hämtar antal siffror per grupp. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Hämtar talets negativa mönster. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Hämtar antal decimaler i procentvärden. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Hämtar decimalavgränsare i procentvärden. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Hämtar gruppavgränsare i procentvärden. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Hämtar antal siffror per grupp för procentvärden. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Hämtar procentens negativa mönster. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Hämtar procentens positiva mönster. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Hämtar procentsymbol. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Hämtar promillesymbol. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Hämtar positiv oändlighetssymbol. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Hämtar positivt tecken. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Hämtar formaterare av specifik typ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Hämtar formaterare associerad med formatleverantören. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [NumberFormatInfo](./numberformatinfo/)() | Standardkonstruktor (invariant [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Hämtar en skrivskyddad version av formateraren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Ställer in antalet decimaler för valuta. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Ställer in valutans decimalavgränsare. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Ställer in valutans gruppavgränsare. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ställer in antalet decimaler per grupp för valuta. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Ställer in valutans negativa mönster. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Ställer in valutans positiva mönster. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Ställer in valutasymbol. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Ställer in ett värde som anger hur siffrors form ska visas. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Ställer in Not-a-Number-symbolen. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ställer in siffersymboler (0 till 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Ställer in negativ oändlighetssymbol. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Ställer in negativt tecken. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Ställer in antal decimaler. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Ställer in decimalavgränsare. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Ställer in talgruppavgränsare. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ställer in antal siffror per grupp. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Ställer in talets negativa mönster. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Ställer in antal decimaler i procentvärden. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Ställer in decimalavgränsare i procentvärden. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Ställer in gruppavgränsare i procentvärden. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ställer in antal siffror per grupp för procentvärden. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Ställer in procentens negativa mönster. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Ställer in procentens positiva mönster. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Ställer in procentsymbol. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Ställer in promillesymbol. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Ställer in positiv oändlighetssymbol. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Ställer in positivt tecken. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställ in det n:te mallargumentet som en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Klass [IFormatProvider](../../system/iformatprovider/)
* Klass [ICloneable](../../system/icloneable/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)