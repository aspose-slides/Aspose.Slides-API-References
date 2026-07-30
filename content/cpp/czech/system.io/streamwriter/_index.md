---
title: StreamWriter
second_title: Aspose.Slides pro C++ API Reference
description: "Representuje zapisovač, který zapisuje znaky do bajtového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 391
url: /cs/system.io/streamwriter/
---
## StreamWriter třída


Representuje zapisovač, který zapisuje znaky do bajtového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Close](./close/)() override | Uzavře stream a uvolní získané prostředky. |
| void [Dispose](./dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a uzavře podkladový stream. |
| virtual void [Dispose](./dispose/)(**bool**) | Uvolní všechny prostředky použité aktuálním objektem a uzavře podkladový stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| void [Flush](./flush/)() override | Vyprázdní obsah vyrovnávací paměti do podkladového streamu a poté vyprázdní podkladový stream. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Vrací hodnotu, která indikuje, zda [StreamWriter](./) vyprázdní data do podkladového streamu při každém volání metody [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Vrací sdílený ukazatel na objekt, který představuje podkladový stream. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Vrací aktuálně používané kódování. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Vrací aktuálně používaný objekt [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Vrací aktuálně používaný objekt [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Vrací řetězec ukončující řádek. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Vrací řetězec ukončující řádek. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# příkazu lock(). Volá se přímo nebo se použije objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# metody [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Vrací hodnotu, která určuje, zda [StreamWriter](./) má při každém volání metody [StreamWriter::Write](./write/) vyprázdnit data do podkladového streamu. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Nastavuje řetězec ukončující řádek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Vytvoří instanci objektu [StreamWriter](./), který zapisuje znaky do určeného podkladového streamu pomocí kódování UTF-8 a vyrovnávací paměti s výchozí velikostí 1024 bajtů. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří instanci objektu [StreamWriter](./), který zapisuje znaky do určeného podkladového streamu pomocí zadaného kódování a vyrovnávací paměti s výchozí velikostí 1024 bajtů. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Vytvoří instanci objektu [StreamWriter](./), který zapisuje znaky do určeného podkladového streamu pomocí zadaného kódování a vyrovnávací paměti dané velikosti. Parametr určuje, zda má být podkladový stream uzavřen při uvolnění objektu [StreamWriter](./). |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Vytvoří instanci objektu [StreamWriter](./), který zapisuje znaky do určeného souboru pomocí kódování UTF-8 a vyrovnávací paměti s výchozí velikostí 1024 bajtů. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří instanci objektu [StreamWriter](./), který zapisuje znaky do určeného souboru pomocí zadaného kódování a vyrovnávací paměti s výchozí velikostí 1024 bajtů. Parametr určuje, zda mají být data přidána do souboru nebo má být soubor přepsán. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Vytvoří instanci objektu [StreamWriter](./), který zapisuje znaky do určeného souboru pomocí zadaného kódování a velikosti vyrovnávací paměti. Parametr určuje, zda mají být data přidána do souboru nebo má být soubor přepsán. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog C# metody [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# příkazu lock(). Volá se přímo nebo se použije objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [Write](./write/)(char_t) override | Zapíše zadaný znak do streamu. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Zapíše zadaný řetězec do streamu. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Zapíše řetězcovou reprezentaci zadaného objektu do streamu. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Zapíše všechny znaky z určeného pole do streamu. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah UTF-16 znaků z určeného pole znaků do streamu. |
| void [Write](./write/)(const char_t *) override | Zapíše zadaný C-řetězec do streamu. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Zapíše řetězcovou reprezentaci zadaného objektu do streamu. |
| virtual void [Write](../textwriter/write/)(**bool**) | Zapíše řetězcovou reprezentaci zadané boolovské hodnoty do streamu. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Zapíše řetězcovou reprezentaci zadaného objektu [Decimal](../../system/decimal/) do streamu. |
| virtual void [Write](../textwriter/write/)(**double**) | Zapíše řetězcovou reprezentaci zadané double-přesné hodnoty s plovoucí řádovou čárkou do streamu. |
| virtual void [Write](../textwriter/write/)(int) | Zapíše řetězcovou reprezentaci zadané 32-bitové celáčkové hodnoty do streamu. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Zapíše řetězcovou reprezentaci zadané 64-bitové celáčkové hodnoty do streamu. |
| virtual void [Write](../textwriter/write/)(**float**) | Zapíše řetězcovou reprezentaci zadané float-přesné hodnoty s plovoucí řádovou čárkou do streamu. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Zapíše řetězcovou reprezentaci zadané unsigned 32-bitové celáčkové hodnoty do streamu. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Zapíše řetězcovou reprezentaci zadané unsigned 64-bitové celáčkové hodnoty do streamu. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../../system/typeinfo/) do streamu. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle zadaného formátu do streamu. |
| void [WriteLine](./writeline/)() override | Zapíše znaky ukončující řádek do streamu. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Zapíše zadaný řetězec následovaný znaky ukončujícími řádek do streamu. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Zapíše řetězcovou reprezentaci zadaného objektu následovanou znaky ukončujícími řádek do streamu. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Zapíše všechny znaky z určeného pole následované znaky ukončujícími řádek do streamu. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah UTF-16 znaků z určeného pole znaků následovaný znaky ukončujícími řádek do streamu. |
| void [WriteLine](./writeline/)(const char_t *) override | Zapíše zadaný C-řetězec následovaný znaky ukončujícími řádek do streamu. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Zapíše řetězcovou reprezentaci zadaného objektu následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Zapíše řetězcovou reprezentaci zadané boolovské hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Zapíše zadaný znak následovaný znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Zapíše řetězcovou reprezentaci zadaného objektu [Decimal](../../system/decimal/) následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Zapíše řetězcovou reprezentaci zadané double-přesné hodnoty s plovoucí řádovou čárkou následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Zapíše řetězcovou reprezentaci zadané 32-bitové celáčkové hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Zapíše řetězcovou reprezentaci zadané 64-bitové celáčkové hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Zapíše řetězcovou reprezentaci zadané float-přesné hodnoty s plovoucí řádovou čárkou následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Zapíše řetězcovou reprezentaci zadané unsigned 32-bitové celáčkové hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Zapíše řetězcovou reprezentaci zadané unsigned 64-bitové celáčkové hodnoty následovanou znaky ukončujícími řádek do streamu. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../../system/typeinfo/) následovanou znaky ukončujícími řádek do streamu. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle zadaného formátu následovanou znaky ukončujícími řádek do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
|  [~StreamWriter](./~streamwriter/)() | Destruktor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Viz také

* Třída [TextWriter](../textwriter/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)