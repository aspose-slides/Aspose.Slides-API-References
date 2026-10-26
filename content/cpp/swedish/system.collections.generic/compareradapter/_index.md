---
title: ComparerAdapter
second_title: Aspose.Slides för C++ API-referens
description: Adapter för att använda IComparer i STL-miljö. Använder IComparer om den är satt; annars används operator < (om tillgänglig) eller returnerar false (om inte).
type: docs
weight: 638
url: /sv/system.collections.generic/compareradapter/
---
## ComparerAdapter struktur

Adapter för att använda [IComparer](../icomparer/) i STL-miljö. Använder [IComparer](../icomparer/) om den är satt; annars används operator < (om tillgänglig) eller returnerar false (om inte).

```cpp
template<class T>class ComparerAdapter
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ som jämförs. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Skapar adapter utan någon jämförare tillgänglig. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Skapar adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funktion för typer med operator < tillgänglig. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funktion för typer utan operator < tillgänglig. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Sätter jämförelseobjekt. |

## Se även

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)