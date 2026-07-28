---
title: EqualityComparerAdapter
second_title: Aspose.Slides dla C++ – referencja API
description: "Adapter umożliwiający użycie IEqualityComparer z kolekcjami i algorytmami w stylu STL. Używa IEqualityComparer, jeśli jest ustawiony. Jeśli nie jest ustawiony, używa operatora ==, Object::Equals lub T::Equals, w zależności od dostępności."
type: docs
weight: 664
url: /pl/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struktura

Adapter umożliwiający użycie [IEqualityComparer](../iequalitycomparer/) z kolekcjami i algorytmami w stylu STL. Używa [IEqualityComparer](../iequalitycomparer/), jeśli jest ustawiony. Jeśli nie jest ustawiony, używa operatora ==, [Object::Equals](../../system/object/equals/) lub T::Equals, w zależności od dostępności.

```cpp
template<class T>class EqualityComparerAdapter
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ będący porównywanym. |

## Metody

| Metoda | Opis |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Tworzy adapter nie używający żadnego komparatora. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Tworzy adapter z podanym komparatorem. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Porównuje dwa obiekty. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Ustawia komparator. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)