---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides pro C++ API Reference
description: Adaptér pro použití IEqualityComparer pro hashování. Používá objekt komparátoru, pokud je nastaven; jinak používá dostupnou hash metodu vybranou pomocí struktury DictionaryHashSelector.
type: docs
weight: 677
url: /cs/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct


Adaptér pro použití [IEqualityComparer](../iequalitycomparer/) pro hashování. Používá objekt porovnávače, pokud je nastaven; jinak používá dostupnou hash metodu vybranou pomocí struktury [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Hashed | typ. |
## Metody

| Metoda | Popis |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Vytvoří adaptér bez komparátoru k použití. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Vytvoří adaptér s daným komparátorem k použití. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Vypočítá hash hodnotu. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Nastaví komparátor k použití. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)