---
title: BinaryReader
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: "Representuje čtečku, která čte primitivní datové typy jako binární data v konkrétním kódování. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to může vést k chybám za běhu a/nebo k selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 92
url: /cs/system.io/binaryreader/
---
## BinaryReader třída

Represents a reader that reads primitive data types as binary data in particular encoding. Objects of this třída should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this třída into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BinaryReader : public System::IDisposable
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Vytvoří instanci třídy [BinaryReader](./), která čte data ze zadaného proudu pomocí kódování UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Vytvoří instanci třídy [BinaryReader](./), která čte data ze zadaného proudu pomocí zadaného kódování. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Vytvoří instanci třídy [BinaryReader](./), která čte data ze zadaného proudu pomocí zadaného kódování. |
| virtual void [Close](./close/)() | Uzavře aktuální objekt [BinaryReader](./) a podkladový vstupní proud. |
| void [Dispose](./dispose/)() override | Uvolní všechny prostředky používané aktuálním objektem a uzavře podkladový proud. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Vrací vstupní proud. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| virtual int [PeekChar](./peekchar/)() | Načte jeden znak ze vstupního proudu bez změny čtecího kurzoru proudu. |
| virtual int [Read](./read/)() | Načte jeden znak ze vstupního proudu. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Načte určený počet bajtů ze vstupního proudu a zapíše je do určeného pole bajtů. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Načte určený počet znaků ze vstupního proudu, převede je na kódování UTF-16 a zapíše výsledné znaky UTF-16 do určeného pole znaků od určené pozice. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Načte jeden bajt ze vstupního proudu a vrátí jeho booleovskou reprezentaci. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Načte jeden bajt ze vstupního proudu. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Načte určený počet bajtů ze vstupního proudu. |
| virtual char_t [ReadChar](./readchar/)() | Načte jeden znak ze vstupního proudu. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Načte určený počet znaků ze vstupního proudu a vrátí je v kódování UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NEIMPLEMENTOVÁNO. |
| virtual **double** [ReadDouble](./readdouble/)() | Načte 8 bajtů ze vstupního proudu a vrátí je jako hodnotu dvojité přesnosti s plovoucí řádovou čárkou. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Načte 2 bajty ze vstupního proudu a vrátí je jako 16bitové celé číslo. |
| virtual int [ReadInt32](./readint32/)() | Načte 4 bajty ze vstupního proudu a vrátí je jako 32bitové celé číslo. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Načte 8 bajtů ze vstupního proudu a vrátí je jako 64bitové celé číslo. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Načte jeden bajt ze vstupního proudu a vrátí jej jako podepsané 8bitové celé číslo. |
| virtual **float** [ReadSingle](./readsingle/)() | Načte 4 bajty ze vstupního proudu a vrátí je jako hodnotu s jednoduchou přesností plovoucí řádové čárky. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Načte řetězec z aktuálního proudu. Řetězec je předponován délkou zakódovanou jako celé číslo po sedmi bitech. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Načte 2 bajty ze vstupního proudu a vrátí je jako 16bitové nezáporné celé číslo. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Načte 4 bajty ze vstupního proudu a vrátí je jako 32bitové nezáporné celé číslo. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Načte 8 bajtů ze vstupního proudu a vrátí je jako 64bitové nezáporné celé číslo. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počet referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý počet referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý počet referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [IDisposable](../../system/idisposable/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)