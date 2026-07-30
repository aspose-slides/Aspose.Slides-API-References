---
title: Enum
second_title: Aspose.Slides pro C++ referenční příručka API
description: Poskytuje metody, které provádějí určité operace s hodnotami typu enum. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem.
type: docs
weight: 1587
url: /cs/system/enum/
---
## Enum struktura

Poskytuje metody, které provádějí určité operace s hodnotami typu enum. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem.

```cpp
template<class E,class Guard>class Enum
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| E | Typ výčtu, jehož hodnoty třída zpracovává |
| Guard | Argument typ služby, jehož účelem je zajistit, že **E** je výčtový typ |

## Metody

| Metoda | Popis |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Provádí aritmetické porovnání hodnot uvedených konstant výčtu. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Vrací název konstanty výčtu, která má zadanou hodnotu. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Vrací název konstanty výčtu, která má zadanou hodnotu. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Vrací pole obsahující názvy všech členů výčtu **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Vrací základní typ výčtu. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Vrací pole obsahující všechny členy výčtu **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Určuje, zda jsou v bitové reprezentaci zadané hodnoty výčtu nastaveny specifikované bity. |
| static **bool** [IsDefined](./isdefined/)(E) | Určuje, zda je zadaná hodnota členem typu výčtu **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Určuje, zda je zadaná hodnota členem typu výčtu **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Určuje, zda je hodnota se zadaným názvem mezi členy výčtu **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Převádí zadaný řetězec na ekvivalentní konstantu výčtu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Zkouší převést zadaný řetězec na ekvivalentní konstantu výčtu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Zkouší převést zadaný řetězec na ekvivalentní konstantu výčtu. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias pro základní typ výčtu. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)