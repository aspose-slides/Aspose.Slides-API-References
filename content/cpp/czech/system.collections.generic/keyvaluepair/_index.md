---
title: KeyValuePair
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Pár klíče a hodnoty. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 378
url: /cs/system.collections.generic/keyvaluepair/
---
## KeyValuePair třída

Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metody

| Metoda | Popis |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Získá klíč. |
| const TValue\& [get_Value](./get_value/)() const | Získá hodnotu. |
| int [GetHashCode](./gethashcode/)() const | Vypočítá hash dvojice klíč-hodnota xorováním hashů klíče a hodnoty. |
| **bool** [IsNull](./isnull/)() const | Vždy vrátí false. |
|  [KeyValuePair](./keyvaluepair/)() | Inicializátor nulového páru klíč-hodnota. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Konstruktor převodu typu. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Záplata pro třídy zděděné z IComparer<KeyValuePair<TKey, TValue>>, neporovnává nic. |
| [String](../../system/string/) [ToString](./tostring/)() const | Převede pár klíč-hodnota na řetězec. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)