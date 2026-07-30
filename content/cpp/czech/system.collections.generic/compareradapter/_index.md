---
title: ComparerAdapter
second_title: Aspose.Slides pro C++ referenci API
description: Adaptér pro použití IComparer v prostředí STL. Používá IComparer, pokud je nastaven; jinak používá operátor < (je-li k dispozici) nebo vrací false (není-li).
type: docs
weight: 638
url: /cs/system.collections.generic/compareradapter/
---
## ComparerAdapter struct


Adaptér pro použití [IComparer](../icomparer/) v prostředí STL. Používá [IComparer](../icomparer/), pokud je nastaven; jinak používá operátor < (je-li k dispozici) nebo vrací false (není-li).

```cpp
template<class T>class ComparerAdapter
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se porovnává. |
## Metody

| Metoda | Popis |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Vytvoří adaptér bez dostupného komparátoru. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Vytvoří adaptér. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funkce pro typy s operátorem < k dispozici. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funkce pro typy bez operátoru <. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Nastaví objekt komparátoru. |

## Viz také

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)