---
title: ColorMatrix
second_title: Aspose.Slides pro C++ API Reference
description: "Představuje matici 5 × 5, která obsahuje souřadnice pro barevný prostor RGBAW. Objektům této třídy by mělo být přidělováno pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 27
url: /cs/system.drawing.imaging/colormatrix/
---
## ColorMatrix třída

Představuje matici 5 × 5, která obsahuje souřadnice pro barevný prostor RGBAW. Objektům této třídy by mělo být přidělováno pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class ColorMatrix : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Vytvoří novou instanci třídy [ColorMatrix](./) a inicializuje ji hodnotami jednotkové matice. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Vytvoří novou instanci třídy [ColorMatrix](./) a inicializuje ji zadanými hodnotami. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní účely. |
| **float** [get_Matrix00](./get_matrix00/)() const | Vrací hodnotu v 0. řádku a 0. sloupci. |
| **float** [get_Matrix01](./get_matrix01/)() const | Vrací hodnotu v 0. řádku a 1. sloupci. |
| **float** [get_Matrix02](./get_matrix02/)() const | Vrací hodnotu v 0. řádku a 2. sloupci. |
| **float** [get_Matrix03](./get_matrix03/)() const | Vrací hodnotu v 0. řádku a 3. sloupci. |
| **float** [get_Matrix04](./get_matrix04/)() const | Vrací hodnotu v 0. řádku a 4. sloupci. |
| **float** [get_Matrix10](./get_matrix10/)() const | Vrací hodnotu v 1. řádku a 0. sloupci. |
| **float** [get_Matrix11](./get_matrix11/)() const | Vrací hodnotu v 1. řádku a 1. sloupci. |
| **float** [get_Matrix12](./get_matrix12/)() const | Vrací hodnotu v 1. řádku a 2. sloupci. |
| **float** [get_Matrix13](./get_matrix13/)() const | Vrací hodnotu v 1. řádku a 3. sloupci. |
| **float** [get_Matrix14](./get_matrix14/)() const | Vrací hodnotu v 1. řádku a 4. sloupci. |
| **float** [get_Matrix20](./get_matrix20/)() const | Vrací hodnotu v 2. řádku a 0. sloupci. |
| **float** [get_Matrix21](./get_matrix21/)() const | Vrací hodnotu v 2. řádku a 1. sloupci. |
| **float** [get_Matrix22](./get_matrix22/)() const | Vrací hodnotu v 2. řádku a 2. sloupci. |
| **float** [get_Matrix23](./get_matrix23/)() const | Vrací hodnotu v 2. řádku a 3. sloupci. |
| **float** [get_Matrix24](./get_matrix24/)() const | Vrací hodnotu v 2. řádku a 4. sloupci. |
| **float** [get_Matrix30](./get_matrix30/)() const | Vrací hodnotu v 3. řádku a 0. sloupci. |
| **float** [get_Matrix31](./get_matrix31/)() const | Vrací hodnotu v 3. řádku a 1. sloupci. |
| **float** [get_Matrix32](./get_matrix32/)() const | Vrací hodnotu v 3. řádku a 2. sloupci. |
| **float** [get_Matrix33](./get_matrix33/)() const | Vrací hodnotu v 3. řádku a 3. sloupci. |
| **float** [get_Matrix34](./get_matrix34/)() const | Vrací hodnotu v 3. řádku a 4. sloupci. |
| **float** [get_Matrix40](./get_matrix40/)() const | Vrací hodnotu v 4. řádku a 0. sloupci. |
| **float** [get_Matrix41](./get_matrix41/)() const | Vrací hodnotu v 4. řádku a 1. sloupci. |
| **float** [get_Matrix42](./get_matrix42/)() const | Vrací hodnotu v 4. řádku a 2. sloupci. |
| **float** [get_Matrix43](./get_matrix43/)() const | Vrací hodnotu v 4. řádku a 3. sloupci. |
| **float** [get_Matrix44](./get_matrix44/)() const | Vrací hodnotu v 4. řádku a 4. sloupci. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Vrací hodnotu na zadaném řádku a sloupci. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Nastaví zadanou hodnotu na určeném místě v matici. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# `is`. |
| void [Lock](../../system/object/lock/)() | Implementuje chování C# `lock()` pro zamykání. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt hodnotového typu s `nullptr` podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počítadlo referencí o zadanou hodnotu. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Nastaví hodnotu v 0. řádku a 0. sloupci. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Nastaví hodnotu v 0. řádku a 1. sloupci. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Nastaví hodnotu v 0. řádku a 2. sloupci. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Nastaví hodnotu v 0. řádku a 3. sloupci. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Nastaví hodnotu v 0. řádku a 4. sloupci. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Nastaví hodnotu v 1. řádku a 0. sloupci. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Nastaví hodnotu v 1. řádku a 1. sloupci. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Nastaví hodnotu v 1. řádku a 2. sloupci. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Nastaví hodnotu v 1. řádku a 3. sloupci. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Nastaví hodnotu v 1. řádku a 4. sloupci. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Nastaví hodnotu v 2. řádku a 0. sloupci. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Nastaví hodnotu v 2. řádku a 1. sloupci. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Nastaví hodnotu v 2. řádku a 2. sloupci. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Nastaví hodnotu v 2. řádku a 3. sloupci. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Nastaví hodnotu v 2. řádku a 4. sloupci. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Nastaví hodnotu v 3. řádku a 0. sloupci. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Nastaví hodnotu v 3. řádku a 1. sloupci. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Nastaví hodnotu v 3. řádku a 2. sloupci. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Nastaví hodnotu v 3. řádku a 3. sloupci. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Nastaví hodnotu v 3. řádku a 4. sloupci. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Nastaví hodnotu v 4. řádku a 0. sloupci. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Nastaví hodnotu v 4. řádku a 1. sloupci. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Nastaví hodnotu v 4. řádku a 2. sloupci. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Nastaví hodnotu v 4. řádku a 3. sloupci. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Nastaví hodnotu v 4. řádku a 4. sloupci. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# `lock()` pro odemčení. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Drawing::Imaging](../)
* Knihovna [Aspose.Slides](../../)