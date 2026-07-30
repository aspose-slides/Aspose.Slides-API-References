---
title: ConsoleOutput
second_title: Aspose.Slides pro C++ – Referenční příručka API
description: "Reprezentuje standardní výstupní proud. Objektům této třídy by mělo být přidělováno pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 209
url: /cs/system/consoleoutput/
---
## ConsoleOutput třída

Reprezentuje standardní výstupní proud. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Zavře proud a uvolní získané prostředky. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a zavře podkladový proud. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Vyprázdní obsah vyrovnávací paměti do podkladového proudu. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Vždy vrací kódování ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Vrací aktuálně používaný [IFormatProvider](../iformatprovider/) objekt. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Vrací aktuálně používaný [IFormatProvider](../iformatprovider/) objekt. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Vrací řetězec ukončující řádek. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Vrací řetězec ukončující řádek. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Nastaví řetězec ukončující řádek. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do režimu slabých. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(**bool**) override | Vypíše řetězcovou reprezentaci zadané bool hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Vypíše řetězcovou reprezentaci zadaného objektu do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(char_t) override | Vypíše zadanou znakovou hodnotu do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)([Decimal](../decimal/)) override | Vypíše řetězcovou reprezentaci hodnoty [Decimal](../decimal/) do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(**double**) override | Vypíše řetězcovou reprezentaci dvojité přesnosti plovoucí desetinné hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(**int32_t**) override | Vypíše řetězcovou reprezentaci 32-bitové celočíselné hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(**int64_t**) override | Vypíše řetězcovou reprezentaci 64-bitové celočíselné hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(**float**) override | Vypíše řetězcovou reprezentaci jednopřesné (single-precision) plovoucí desetinné hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const [String](../string/)\&) override | Vypíše zadaný řetězcový objekt do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(**uint32_t**) override | Vypíše řetězcovou reprezentaci nepodepsané 32-bitové celočíselné hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(**uint64_t**) override | Vypíše řetězcovou reprezentaci nepodepsané 64-bitové celočíselné hodnoty do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Vypíše řetězcovou reprezentaci zadaného pole znaků do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Vypíše řetězcovou reprezentaci rozsahu hodnot zadaného pole znaků do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const char_t *) override | Vypíše zadaný c-string do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Vypíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../typeinfo/) do výstupního proudu reprezentovaného aktuálním objektem. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Zapíše řetězcovou reprezentaci zadané 32-bitové celočíselné hodnoty do proudu. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle specifikovaného formátu do proudu. |
| void [WriteLine](./writeline/)() override | Vypíše aktuální ukončovač řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Vypíše řetězcovou reprezentaci zadaného objektu následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(**bool**) override | Vypíše řetězcovou reprezentaci zadané bool hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(char_t) override | Vypíše zadaný znak následovaný aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Vypíše řetězcovou reprezentaci hodnoty [Decimal](../decimal/) následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(**double**) override | Vypíše řetězcovou reprezentaci dvojité přesnosti plovoucí desetinné hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(int) override | Vypíše řetězcovou reprezentaci 32-bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(**int64_t**) override | Vypíše řetězcovou reprezentaci 64-bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(**float**) override | Vypíše řetězcovou reprezentaci jednopřesné plovoucí desetinné hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Vypíše zadaný řetězcový objekt následovaný aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Vypíše řetězcovou reprezentaci nepodepsané 32-bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Vypíše řetězcovou reprezentaci nepodepsané 64-bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Vypíše řetězcovou reprezentaci zadaného pole znaků následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Vypíše řetězcovou reprezentaci rozsahu hodnot zadaného pole znaků následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const char_t *) override | Vypíše zadaný c-string následovaný aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Vypíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../typeinfo/) následovanou aktuálním ukončovačem řádku do výstupního proudu reprezentovaného aktuálním objektem. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle specifikovaného formátu následované znakem ukončujícím řádek do proudu. |
| virtual  [~Object](../object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destruktor. |

## Viz také

* Třída [TextWriter](../../system.io/textwriter/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)