---
title: BinaryWriter
second_title: Aspose.Slides pro C++ – API reference
description: "Representuje zapisovač, který zapisuje hodnoty primitivních typů do bytového proudu. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a používejte tento ukazatel při předávání jako argument funkcím."
type: docs
weight: 105
url: /cs/system.io/binarywriter/
---
## BinaryWriter třída


Represents a writer that writes values of primitive types to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BinaryWriter : public System::IDisposable
```

## Metody

| Method | Description |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Vytvoří instanci třídy [BinaryWriter](./), která zapisuje data do určeného proudu pomocí určeného kódování. |
| void [Close](./close/)() | Uzavře aktuální objekt [BinaryWriter](./) a podkladový výstupní proud. |
| void [Dispose](./dispose/)() override | Uvolní veškeré prostředky použité aktuálním objektem a uzavře podkladový proud. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typových hodnot ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| void [Flush](./flush/)() | Vyprázdní výstupní proud. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Vrací výstupní proud. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci odvozených tříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci odvozených tříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referenčně objekt typové hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počítadlo referencí o zadanou hodnotu. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Nastaví pozici proudu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožní přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Write](./write/)(**uint8_t**) | Zapíše zadanou neznačkovou 8-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Zapíše zadaný podrozsah bytů ze zadaného pole bytů do výstupního proudu. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Zapíše zadaný podrozsah znaků UTF-16 ze zadaného pole znaků do výstupního proudu. |
| virtual void [Write](./write/)(**bool**) | Zapíše jeden byte s hodnotou 0, pokud je **value** 'true', a 1, pokud je **value** 'false', do výstupního proudu. |
| virtual void [Write](./write/)(char16_t) | Zapíše zadaný 16-bitový široký znak do výstupního proudu. |
| virtual void [Write](./write/)(**int16_t**) | Zapíše zadanou 16-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(int) | Zapíše zadanou 32-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(**int64_t**) | Zapíše zadanou 64-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(**uint16_t**) | Zapíše zadanou neznačkovou 16-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(**uint32_t**) | Zapíše zadanou neznačkovou 32-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(**uint64_t**) | Zapíše zadanou neznačkovou 64-bitovou celočíselnou hodnotu do výstupního proudu. |
| virtual void [Write](./write/)(**float**) | Zapíše zadanou hodnotu s jednoduchou přesností do výstupního proudu. |
| virtual void [Write](./write/)(**double**) | Zapíše zadanou dvojitou přesnost (double) do výstupního proudu. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Zapíše bajtové vyjádření zadané hodnoty [Decimal](../../system/decimal/) do výstupního proudu. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Zapíše řetězec s předponou délky v aktuálním kódování do výstupního proudu. |
| virtual void [Write](./write/)(const char_t *) | Zapíše řetězec s předponou délky v aktuálním kódování do výstupního proudu. |
|  [~BinaryWriter](./~binarywriter/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IDisposable](../../system/idisposable/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)