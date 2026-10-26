---
title: NumberFormatInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Bevat informatie over hoe getallen te formatteren. Setter-bewerkingen zijn alleen ingeschakeld op objecten die geen alleen-lees zijn. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit tot runtime-fouten en/of assertiefouten leidt. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 248
url: /nl/system.globalization/numberformatinfo/
---
## NumberFormatInfo klasse


Bevat informatie over hoe getallen te formatteren. Instelbewerkingen zijn alleen ingeschakeld op objecten die niet alleen-lees zijn. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Methoden

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Kloont formatinfo. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Haalt het aantal valutadecimale cijfers op. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Haalt het valutadecimale scheidingsteken op. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Haalt het valutagroepscheidingsteken op. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Haalt het aantal valutadecimale cijfers per groep op. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Haalt het negatieve valutapatroon op. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Haalt het positieve valutapatroon op. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Haalt het valutasymbool op. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Haalt de door de huidige threadcultuur gedefinieerde nummeropmaakinformatie op. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Haalt een waarde op die aangeeft hoe de vorm van een cijfer moet worden weergegeven. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Haalt de door een invariante cultuur gedefinieerde nummeropmaakinformatie op. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Controleert of de opmaak alleen-lees is. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Haalt het Not-a-Number-symbool op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Haalt de cijfer-symbolen op (0 tot en met 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Haalt het symbool voor negatieve oneindigheid op. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Haalt het negatieve teken op. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Haalt het aantal decimale cijfers op. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Haalt het decimale scheidingsteken op. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Haalt het getalgroepscheidingsteken op. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Haalt het aantal cijfers per groep op. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Haalt het negatieve getalpatroon op. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Haalt het aantal decimale plaatsen in procentwaarden op. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Haalt het decimale scheidingsteken in procentwaarden op. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Haalt het groeperingsscheidingsteken in procentwaarden op. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Haalt het aantal cijfers per procentwaarde-groep op. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Haalt het negatieve percentpatroon op. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Haalt het positieve percentpatroon op. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Haalt het percent-symbool op. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Haalt het permille-symbool op. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Haalt het symbool voor positieve oneindigheid op. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Haalt het positieve teken op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Haalt de formatter van een specifiek type op. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Haalt de formatter op die gekoppeld is aan de formatprovider. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschreven door targetType vertegenwoordigt. Analoge van C# 'is'-operator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [NumberFormatInfo](./numberformatinfo/)() | Standaardconstructor (invariante [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Haalt de alleen-lees versie van de formatter op. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Stelt het aantal valutadecimale cijfers in. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Stelt het valutadecimale scheidingsteken in. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Stelt het valutagroepscheidingsteken in. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Stelt het aantal valutadecimale cijfers per groep in. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Stelt het negatieve valutapatroon in. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Stelt het positieve valutapatroon in. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Stelt het valutasymbool in. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Stelt een waarde in die aangeeft hoe de vorm van een cijfer moet worden weergegeven. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Stelt het Not-a-Number-symbool in. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt de cijfer-symbolen in (0 tot en met 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Stelt het symbool voor negatieve oneindigheid in. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Stelt het negatieve teken in. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Stelt het aantal decimale cijfers in. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Stelt het decimale scheidingsteken in. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Stelt het getalgroepscheidingsteken in. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Stelt het aantal cijfers per groep in. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Stelt het negatieve getalpatroon in. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Stelt het aantal decimale plaatsen in procentwaarden in. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Stelt het decimale scheidingsteken in procentwaarden in. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Stelt het groeperingsscheidingsteken in procentwaarden in. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Stelt het aantal cijfers per procentwaarde-groep in. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Stelt het negatieve percentpatroon in. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Stelt het positieve percentpatroon in. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Stelt het percent-symbool in. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Stelt het permille-symbool in. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Stelt het symbool voor positieve oneindigheid in. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Stelt het positieve teken in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |
## Zie ook

* Klasse [Object](../../system/object/)
* Klasse [IFormatProvider](../../system/iformatprovider/)
* Klasse [ICloneable](../../system/icloneable/)
* Naamruimte [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)