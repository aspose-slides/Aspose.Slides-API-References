---
title: CompareInfo
second_title: Aspose.Slides pro C++ referenční příručka
description: "Provádí porovnávání řetězců citlivé na kulturu. Objektům této třídy by se mělo alokovat pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním assercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 40
url: /cs/system.globalization/compareinfo/
---
## CompareInfo třída

Makes culture-sensitive string comparison. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CompareInfo : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Porovnává řetězce. Není implementováno. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Porovnává řetězce. Podporovány jsou pouze režimy Ordinal a OrdinalIgnoreCase. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Porovnává část jednoho řetězce s částí druhého řetězce. Není implementováno. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Porovnává koncovou část jednoho řetězce s koncovou částí druhého řetězce pomocí metod porovnávání řetězců. Není implementováno. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Porovnává koncovou část jednoho řetězce s koncovou částí druhého řetězce. Není implementováno. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Porovnává část jednoho řetězce s částí druhého řetězce pomocí metod porovnávání řetězců. Není implementováno. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | Informace RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| int [get_LCID](./get_lcid/)() const | Získá LCID kultury spojené s porovnávačem. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Získá název kultury spojené s porovnávačem. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Získá informace o verzi řazení. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Získá [CompareInfo](./) spojené se zadanou kulturou a používající metody porovnávání řetězců ve specifikovaném sestavení. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Získá [CompareInfo](./) spojené se zadanou kulturou a používající metody porovnávání řetězců ve specifikovaném sestavení. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Získá [CompareInfo](./) spojené se zadanou kulturou. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Získá [CompareInfo](./) spojené se zadanou kulturou. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Získá hash kód řetězce na základě zadaných možností porovnání. |
| int [GetHashCode](./gethashcode/)() const override | Analog C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Získá [SortKey](../sortkey/) objekt pro zadaný řetězec pomocí zadaných možností porovnání. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Získá [SortKey](../sortkey/) objekt pro zadaný řetězec. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Hledá podřetězec. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Hledá podřetězec. Podporován je pouze režim Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Hledá podřetězec. Podporován je pouze režim Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Hledá zadaný znak. Podporován je pouze režim Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Hledá podřetězec. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Hledá zadaný znak. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Hledá podřetězec. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Hledá zadaný znak. Podporován je pouze režim Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Hledá zadaný znak. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Hledá zadaný znak. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Hledá podřetězec. Podporován je pouze režim Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Hledá zadaný znak. Podporován je pouze režim Ordinal. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Zkontroluje, zda zadaný řetězec začíná zadanou předponou pomocí zadaných možností porovnání. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Zkontroluje, zda zadaný řetězec začíná zadanou předponou. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Zkontroluje, zda je zadaný znak řaditelný. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Zkontroluje, zda je zadaný řetězec řaditelný. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Zkontroluje, zda zadaný řetězec končí zadanou příponou pomocí zadaných možností porovnání. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Zkontroluje, zda zadaný řetězec končí zadanou příponou. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Vyhledá poslední výskyt zadaného podřetězce. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Vyhledá poslední výskyt zadaného podřetězce pomocí zadaných možností porovnání. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Vyhledá poslední výskyt zadaného znaku pomocí zadaných možností porovnání. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Vyhledá poslední výskyt zadaného řetězce. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Vyhledá poslední výskyt zadaného řetězce pomocí zadaných možností porovnání. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Vyhledá poslední výskyt zadaného znaku pomocí zadaných možností porovnání. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Vyhledá poslední výskyt zadaného řetězce. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Vyhledá poslední výskyt zadaného znaku. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Vyhledá poslední výskyt zadaného řetězce pomocí zadaných možností porovnání. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Vyhledá poslední výskyt zadaného znaku pomocí zadaných možností porovnání. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Vyhledá poslední výskyt zadaného znaku. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Vyhledá poslední výskyt zadaného znaku. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt hodnotového typu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počet referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)