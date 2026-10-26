---
title: StringBuilder
second_title: Aspose.Slides pro C++ API Reference
description: "Buffer pro akumulaci řetězce po částech. Tento typ může být alokován buď na zásobníku jako typ hodnoty, nebo v haldě pomocí funkce System::MakeObject() function. Jakmile je objekt alokován, nikdy neprovádějte smíchání těchto dvou případů použití: mít SmartPtr ukazatele na objekty alokované na zásobníku je přísně zakázáno."
type: docs
weight: 326
url: /cs/system.text/stringbuilder/
---
## StringBuilder třída


[Buffer](../../system/buffer/) k akumulaci řetězce po částech. Tento typ může být alokován buď na zásobníku jako hodnota, nebo v haldě pomocí funkce [System::MakeObject()](../../system/makeobject/). Jakmile je objekt alokován, nikdy nemíchejte tyto dva případy použití: mít [SmartPtr](../../system/smartptr/) ukazatele na objekty alokované na zásobníku je přísně zakázáno.

```cpp
class StringBuilder : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Přidá znak do builderu. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Přidá znaky do builderu. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Přidá pole znaků do builderu. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Přidá část pole znaků do builderu. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Přidá řetězec do builderu. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Přidá část řetězce do builderu. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Přidá řetězcovou reprezentaci objektu do builderu. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Přidá obsah builderu do builderu. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Přidá hodnotu s plovoucí desetinnou čárkou do builderu. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Přidá hodnotu s plovoucí desetinnou čárkou do builderu. |
| [StringBuilder](./) * [Append](./append/)(int) | Přidá celočíselnou hodnotu do builderu. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Přidá aritmetickou hodnotu do builderu. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Přidá řetězcovou reprezentaci enum hodnoty do builderu. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Připojí formátovaný řetězec do builderu. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Připojí formátovaný řetězec do builderu. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Připojí znak nového řádku do builderu. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Připojí řetězec následovaný znakem nového řádku do builderu. |
| [StringBuilder](./) * [Clear](./clear/)() | Odstraní všechny znaky z builderu. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Zkopíruje data builderu do existujících pozic pole. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Zajišťuje, že kapacita této instance [System.Text.StringBuilder](./) je alespoň zadaná hodnota. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| int [get_Capacity](./get_capacity/)() const | Získá aktuální kapacitu řetězcového builderu. |
| int [get_Length](./get_length/)() const | Získá délku řetězce aktuálně v builderu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| char_t [idx_get](./idx_get/)(int) const | Získá znak na zadané pozici. |
| void [idx_set](./idx_set/)(int, char_t) | Nastaví znak na zadané pozici. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Vloží řetězec do pevné pozice builderu. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Vloží opakovaný řetězec do pevné pozice builderu. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Vloží znak do pevné pozice builderu. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Vloží znaky do pevné pozice builderu. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Vloží hodnotu do pevné pozice builderu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) strážní objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| char_t [operator[]](./operator[]/)(int) const | Získá znak na zadané pozici. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Odstraní fragment z builderu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Nahradí podřetězec v builderu. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Nahradí podřetězec v rozsahu builderu. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Nahradí znak v builderu. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Nahradí znak v rozsahu builderu. |
| void [set_Capacity](./set_capacity/)(int) | Nastaví aktuální kapacitu řetězcového builderu. |
| void [set_Length](./set_length/)(int) | Zkrátí nebo prodlouží řetězcový builder na zadanou délku. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Konstruktor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Získá řetězec aktuálně obsažený v builderu. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Získá podřetězec aktuálně obsažený v builderu. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) strážní objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
|  [~StringBuilder](./~stringbuilder/)() | Destruktor. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Text](../)
* Knihovna [Aspose.Slides](../../)