---
title: EqualityComparerAdapter
second_title: Aspose.Slides pro referenční příručku API C++
description: "Adaptér umožňující použití IEqualityComparer s kolekcemi a algoritmy ve stylu STL. Používá IEqualityComparer, pokud je nastaven. Pokud není nastaven, používá operátor ==, Object::Equals nebo T::Equals, podle toho, co je k dispozici."
type: docs
weight: 664
url: /cs/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct


Adaptér umožňující použití [IEqualityComparer](../iequalitycomparer/) s kolekcemi a algoritmy ve stylu STL. Používá [IEqualityComparer](../iequalitycomparer/), pokud je nastaven. Pokud není nastaven, používá operátor ==, [Object::Equals](../../system/object/equals/) nebo T::Equals, podle toho, co je k dispozici.

```cpp
template<class T>class EqualityComparerAdapter
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se porovnává. |
## Metody

| Metoda | Popis |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Vytvoří adaptér nepoužívající žádný komparátor. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Vytvoří adaptér s daným komparátorem. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Porovná dva objekty. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Nastaví komparátor. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)