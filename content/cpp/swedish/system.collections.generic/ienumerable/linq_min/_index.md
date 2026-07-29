---
title: LINQ_Min()
second_title: Aspose.Slides för C++ API-referens
description: Anropar en transform-funktion på varje element i en generisk sekvens och returnerar det minsta resulterande värdet.
type: docs
weight: 339
url: /sv/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) metod


Anropar en transform-funktion på varje element i en generisk sekvens och returnerar det minsta resulterande värdet.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av selector. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | En transform-funktion att tillämpa på varje element. |

### Returvärde

Det minsta värdet i sekvensen.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) metod




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Se även

* Klass [Func](../../../system/func/)
* Klass [IEnumerable](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)