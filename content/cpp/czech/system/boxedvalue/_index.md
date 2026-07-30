---
title: BoxedValue
second_title: Aspose.Slides pro C++ API Reference
description: "Zastupuje zabalenou hodnotu. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 105
url: /cs/system/boxedvalue/
---
## BoxedValue třída


Zastupuje zabalenou hodnotu. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| T | Type of the boxed value represented by the class |
## Metody

| Method | Description |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | Vytvoří objekt, který představuje zadanou zabalenou hodnotu. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Určuje rovnost zabalených hodnot reprezentovaných aktuálním a zadaným objektem. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání dvojité přesnosti ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| int [GetHashCode](./gethashcode/)() const override | Vrací hash kód pro aktuální objekt. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Získá skutečný typ objektu. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | Vrací hodnotu představující typ zabalené hodnoty reprezentované aktuálním objektem. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Vrací číselnou hodnotu zabaleného objektu, pokud lze provést přetypování, jinak vrací nulu. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| **bool** [is](./is/)() const | Určuje, zda typ zabalené hodnoty reprezentované aktuálním objektem je **V**. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Určuje, zda aktuální objekt představuje zabalenou hodnotu výčtového typu. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci odvozených tříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci odvozených tříd. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Zabaluje hodnotu konstanty výčtu zadaného výčtu s určeným názvem. Parametr určuje, zda má být při interpretaci řetězce specifikujícího název konstanty výčtu ignorována velikost písmen. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Zabaluje hodnotu konstanty výčtu zadaného výčtu s určeným názvem. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Sníží počítadlo sdílených referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvětší počítadlo sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Sníží a vrátí počítadlo sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Převede zabalenou hodnotu reprezentovanou aktuálním objektem na řetězec. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Převede zabalený objekt na řetězec pomocí zadaného formátovacího řetězce. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Rozbalí hodnotu reprezentovanou aktuálním objektem. |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí pomocí výrazu C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvětší počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Sníží počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [BoxedValueBase](../boxedvaluebase/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)