---
title: operator()()
second_title: Aspose.Slides för C++ API-referens
description: Jämförelsefunktion för typer med operator < tillgänglig.
type: docs
weight: 27
url: /sv/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const metod

[Comparison](../../../system/comparison/) funktion för typer med operator < tillgänglig.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ som jämförs; mall för tillgänglighet för typkonvertering. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const Q\& | Första värdet att jämföra. |
| y | const Q\& | Andra värdet att jämföra. |

### Returvärde

Sant om **x** anses vara mindre än **y**, falskt annars.

## ComparerAdapter::operator()(const Q\&, const Q\&) const metod

[Comparison](../../../system/comparison/) funktion för typer med operator < ej tillgänglig.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ som jämförs; mall för tillgänglighet för typkonvertering. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const Q\& | Första värdet att jämföra. |
| y | const Q\& | Andra värdet att jämföra. |

### Returvärde

Sant om komparatorn är inställd och **x** anses vara mindre än **y**, falskt annars.

## Se även

* Struktur [ComparerAdapter](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)