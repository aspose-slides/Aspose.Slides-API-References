---
title: NumberFormatInfo
second_title: Aspose.Slides pro C++ API Reference
description: "Obsahuje informace o tom, jak formátovat čísla. Operace nastavení jsou povoleny pouze u objektů, které nejsou pouze pro čtení. Objektům této třídy by mělo být přiřazeno pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 248
url: /cs/system.globalization/numberformatinfo/
---
## NumberFormatInfo třída

Obsahuje informace o tom, jak formátovat čísla. Operace nastavování jsou povoleny pouze u objektů, které nejsou pouze pro čtení. Objektům této třídy by mělo být přiřazeno pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Metody

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonuje informace o formátu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Získá počet desetinných číslic měny. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Získá oddělovač desetinných míst měny. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Získá oddělovač skupiny měny. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Získá počet desetinných číslic měny na skupinu. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Získá vzor záporné měny. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Získá vzor kladné měny. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Získá symbol měny. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Získá informace o formátu čísel definované kulturou aktuálního vlákna. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Získá hodnotu, která určuje, jak zobrazit tvar číslice. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Získá informace o formátu čísel definované invariantní kulturou. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Kontroluje, zda je formát jen pro čtení. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Získá symbol Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Získá symboly číslic (0 až 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Získá symbol záporného nekonečna. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Získá záporné znaménko. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Získá počet desetinných číslic. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Získá desetinný oddělovač. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Získá oddělovač skupiny čísel. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Získá počet číslic v jedné skupině. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Získá vzor záporného čísla. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Získá počet desetinných míst v procentech. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Získá desetinný oddělovač v procentech. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Získá oddělovač skupin v procentech. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Získá počet číslic v jedné skupině procent. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Získá vzor záporného procenta. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Získá vzor kladného procenta. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Získá symbol procenta. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Získá symbol promile. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Získá symbol kladného nekonečna. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Získá kladné znaménko. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu reference counteru spojenou s objektem. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Získá formátovač konkrétního typu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Získá formátovač spojený s poskytovatelem formátu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [NumberFormatInfo](./numberformatinfo/)() | Výchozí konstruktor (invariantní [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktérů podtříd. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktérů podtříd. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Získá verzi formátovače pouze pro čtení. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených referencí o zadanou hodnotu. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Nastaví počet desetinných číslic měny. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Nastaví oddělovač desetinných míst měny. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Nastaví oddělovač skupiny měny. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Nastaví počet desetinných číslic měny na skupinu. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Nastaví vzor záporné měny. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Nastaví vzor kladné měny. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Nastaví symbol měny. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Nastaví hodnotu, která určuje, jak zobrazit tvar číslice. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Nastaví symbol Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Nastaví symboly číslic (0 až 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Nastaví symbol záporného nekonečna. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Nastaví záporné znaménko. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Nastaví počet desetinných číslic. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Nastaví desetinný oddělovač. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Nastaví oddělovač skupiny čísel. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Nastaví počet číslic v jedné skupině. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Nastaví vzor záporného čísla. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Nastaví počet desetinných míst v procentech. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Nastaví desetinný oddělovač v procentech. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Nastaví oddělovač skupin v procentech. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Nastaví počet číslic v jedné skupině procent. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Nastaví vzor záporného procenta. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Nastaví vzor kladného procenta. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Nastaví symbol procenta. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Nastaví symbol promile. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Nastaví symbol kladného nekonečna. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Nastaví kladné znaménko. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počitadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení příkazu C# lock(). Volá se přímo nebo pomocí objektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Třída [IFormatProvider](../../system/iformatprovider/)
* Třída [ICloneable](../../system/icloneable/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)