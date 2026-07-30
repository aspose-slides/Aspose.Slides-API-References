---
title: Random
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje pseudo-náhodný generátor čísel. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to může vést k chybám za běhu a/nebo k selháním asertací. Vždy obalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 1184
url: /cs/system/random/
---
## Třída Random


Reprezentuje pseudo-náhodný generátor čísel. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním asertací. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class Random : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| **bool** [IsNull](./isnull/)() const | Vždy vrací false. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí C# výrazu lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| virtual **int32_t** [Next](./next/)() | Vrátí nezáporné náhodné číslo menší než maximální hodnota int32. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | Vrátí nezáporné náhodné číslo menší než zadané maximum. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | Vrátí náhodné číslo v zadaném rozsahu. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Vyplní prvky zadaného pole bajtů náhodnými čísly. |
| virtual **double** [NextDouble](./nextdouble/)() | Vrátí náhodné číslo mezi 0,0 a 1,0. |
|  [Object](../object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
|  [Random](./random/)() | Inicializuje novou instanci pomocí časově závislé výchozí semínkové hodnoty. |
|  [Random](./random/)(**int32_t**) | Inicializuje novou instanci třídy [System.Random](./) pomocí zadané semínkové hodnoty. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvýší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí pomocí C# výrazu lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvýší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |
## Poznámky



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Získá náhodné číslo měsíce a vytiskne jej.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Naplní pole náhodnými čísly.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Vytiskne pole.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
Tento příklad kódu produkuje následující výstup:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## Viz také

* Třída [Object](../object/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)