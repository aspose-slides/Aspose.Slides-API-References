---
title: LINQ_Max()
second_title: Aspose.Slides för C++ API-referens
description: Anropar en transformfunktion på varje element i en generisk sekvens och returnerar det maximala resulterande värdet.
type: docs
weight: 352
url: /sv/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metod


Anropar en transformfunktion på varje element i en generisk sekvens och returnerar det maximala resulterande värdet.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen på värdet som returneras av selector. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | En transformfunktion att tillämpa på varje element. |

### Returvärde

Det maximala värdet i sekvensen.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metod




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Se även

* Klass [Func](../../../system/func/)
* Klass [IEnumerable](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)