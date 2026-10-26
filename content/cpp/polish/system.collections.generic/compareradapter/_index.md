---
title: ComparerAdapter
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Adapter umożliwiający użycie IComparer w środowisku STL. Używa IComparer, jeśli jest ustawiony; w przeciwnym razie używa operatora < (jeśli jest dostępny) lub zwraca false (jeśli nie jest).
type: docs
weight: 638
url: /pl/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adapter umożliwiający użycie [IComparer](../icomparer/) w środowisku STL. Używa [IComparer](../icomparer/), jeśli jest ustawiony; w przeciwnym razie używa operatora < (jeśli jest dostępny) lub zwraca false (jeśli nie jest).

```cpp
template<class T>class ComparerAdapter
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ porównywany. |

## Metody

| Metoda | Opis |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Tworzy adapter bez dostępnego komparatora. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Tworzy adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funkcja dla typów, w których dostępny jest operator <. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funkcja dla typów, w których operator < nie jest dostępny. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Ustawia obiekt komparatora. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)