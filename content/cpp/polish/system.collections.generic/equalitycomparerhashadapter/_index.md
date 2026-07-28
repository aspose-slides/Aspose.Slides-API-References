---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides dla C++ – odniesienie API
description: Adapter używający IEqualityComparer do haszowania. Używa obiektu porównywacza, jeśli jest ustawiony; w przeciwnym razie używa dostępnej metody haszowania wybranej przy użyciu struktury DictionaryHashSelector.
type: docs
weight: 677
url: /pl/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct


Adapter używający [IEqualityComparer](../iequalitycomparer/) do haszowania. Używa obiektu porównywacza, jeśli jest ustawiony; w przeciwnym razie używa dostępnej metody haszowania wybranej przy użyciu struktury [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Hashed | typ. |
## Metody

| Metoda | Opis |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Tworzy adapter bez porównywacza do użycia. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Tworzy adapter z podanym porównywaczem do użycia. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Oblicza wartość haszu. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Ustawia porównywacz do użycia. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)