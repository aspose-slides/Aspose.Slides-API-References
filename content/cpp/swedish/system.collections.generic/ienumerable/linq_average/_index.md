---
title: LINQ_Average()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar medelvärdet av en sekvens av numeriska värden.
type: docs
weight: 365
url: /sv/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() metod

Beräknar medelvärdet av en sekvens av numeriska värden.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### Returvärde

Medelvärdet av värdena i sekvensen.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) metod

Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transformfunktion på varje element i indatasekvensen.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av selector. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | En transformfunktion att applicera på varje element. |

### Returvärde

Medelvärdet av de projicerade värdena.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) metod


```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Se även

* Klass [IEnumerable](../)
* Klass [Func](../../../system/func/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)