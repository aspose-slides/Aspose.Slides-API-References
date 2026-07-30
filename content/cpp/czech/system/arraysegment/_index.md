---
title: ArraySegment
second_title: Aspose.Slides pro C++ – reference API
description: "Zastupuje úsek jednorozměrného pole. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 40
url: /cs/system/arraysegment/
---
## ArraySegment třída


Zastupuje úsek jednorozměrného pole. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte [System::SmartPtr](../smartptr/) třídu k řízení objektů tohoto typu.

```cpp
template<typename T>class ArraySegment : public System::Object
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků úseku pole. |
## Metody

| Metoda | Popis |
| --- | --- |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>) |  |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>, **int32_t**, **int32_t**) |  |
|  [ArraySegment](./arraysegment/)() |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([ArraySegment](./)\<T\>) |  |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::ArrayPtr](../arrayptr/)\<T\> [get_Array](./get_array/)() const |  |
| **int32_t** [get_Count](./get_count/)() const |  |
| **int32_t** [get_Offset](./get_offset/)() const |  |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte [LockContext](../lockcontext/) strážní objekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| T\& [operator[]](./operator[]/)(**int32_t**) const |  |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty referencí. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty referencí. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Sníží počet sdílených referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvětší počet sdílených referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [ArraySegment](./)\<T\> [Slice](./slice/)(**int32_t**, **int32_t**) |  |
| [System::ArrayPtr](../arrayptr/)\<T\> [ToArray](./toarray/)() const |  |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odemykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte [LockContext](../lockcontext/) strážní objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvýší počet slabých referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Sníží počet slabých referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Poznámky



```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Vytvoří a naplní pole.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Vytvoří úsek pole, který obsahuje celé pole.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Vytiskne položky úseku pole.
  Print(fullArray);

  // Vytvoří úsek pole.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Vytiskne položky úseku pole.
  Print(segment);

  return 0;
}
/*
Tento příklad kódu produkuje následující výstup:
First Second Third
Second Third
*/
```

## Viz také

* Třída [Object](../object/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)