---
title: TextWriter
second_title: Aspose.Slides pro C++ API Referenci
description: "Základní třída pro třídy, které představují zapisovače zapisující sekvence znaků do různých destinací. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 443
url: /cs/system.io/textwriter/
---
## TextWriter třída

Základní třída pro třídy, které představují zapisovače zapisující sekvence znaků do různých destinací. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class TextWriter : public System::IDisposable
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Uzavře stream a uvolní získané prostředky. |
| void [Dispose](./dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a uzavře podkladový stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [Flush](./flush/)() | Vyprázdní obsah vyrovnávací paměti do podkladového streamu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Vrací aktuálně používané kódování. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Vrací aktuálně používaný objekt [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Vrací aktuálně používaný objekt [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Vrací řetězec ukončující řádek. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Vrací řetězec ukončující řádek. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci objektu hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Nastaví řetězec ukončující řádek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# příkazu lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapíše řetězcovou reprezentaci zadaného objektu do streamu. |
| virtual void [Write](./write/)(**bool**) | Zapíše řetězcovou reprezentaci zadané booleovské hodnoty do streamu. |
| virtual void [Write](./write/)(char_t) | Zapíše zadaný znak do streamu. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Zapíše řetězcovou reprezentaci zadaného objektu [Decimal](../../system/decimal/) do streamu. |
| virtual void [Write](./write/)(**double**) | Zapíše řetězcovou reprezentaci zadané hodnoty typu double do streamu. |
| virtual void [Write](./write/)(int) | Zapíše řetězcovou reprezentaci zadané 32bitové celočíselné hodnoty do streamu. |
| virtual void [Write](./write/)(**int64_t**) | Zapíše řetězcovou reprezentaci zadané 64bitové celočíselné hodnoty do streamu. |
| virtual void [Write](./write/)(**float**) | Zapíše řetězcovou reprezentaci zadané hodnoty typu float do streamu. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Zapíše zadaný řetězec do streamu. |
| virtual void [Write](./write/)(**uint32_t**) | Zapíše řetězcovou reprezentaci zadané 32bitové unsigned celočíselné hodnoty do streamu. |
| virtual void [Write](./write/)(**uint64_t**) | Zapíše řetězcovou reprezentaci zadané 64bitové unsigned celočíselné hodnoty do streamu. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapíše všechny znaky ze zadaného pole do streamu. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah znaků UTF-16 ze zadaného pole znaků do streamu. |
| virtual void [Write](./write/)(const char_t *) | Zapíše zadaný c-string do streamu. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../../system/typeinfo/) do streamu. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle zadaného formátu do streamu. |
| virtual void [WriteLine](./writeline/)() | Zapíše znaky ukončující řádek do streamu. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapíše řetězcovou reprezentaci zadaného objektu následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(**bool**) | Zapíše řetězcovou reprezentaci zadané booleovské hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(char_t) | Zapíše zadaný znak následovaný znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Zapíše řetězcovou reprezentaci zadaného objektu [Decimal](../../system/decimal/) následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(**double**) | Zapíše řetězcovou reprezentaci zadané hodnoty typu double následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(int) | Zapíše řetězcovou reprezentaci zadané 32bitové celočíselné hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Zapíše řetězcovou reprezentaci zadané 64bitové celočíselné hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(**float**) | Zapíše řetězcovou reprezentaci zadané hodnoty typu float následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Zapíše zadaný řetězec následovaný znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Zapíše řetězcovou reprezentaci zadané 32bitové unsigned celočíselné hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Zapíše řetězcovou reprezentaci zadané 64bitové unsigned celočíselné hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapíše všechny znaky ze zadaného pole následované znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah znaků UTF-16 ze zadaného pole znaků následovaný znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Zapíše zadaný c-string následovaný znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../../system/typeinfo/) následovanou znaky ukončujícími řádek do streamu. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle zadaného formátu následovanou znaky ukončujícími řádek do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |
| virtual  [~TextWriter](./~textwriter/)() | Destruktor. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na tuto třídu. |

## Viz také

* Třída [IDisposable](../../system/idisposable/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)