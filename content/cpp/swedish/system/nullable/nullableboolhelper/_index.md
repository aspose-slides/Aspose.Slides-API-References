---
title: NullableBoolHelper()
second_title: Aspose.Slides för C++ API-referens
description: Hjälpfunktion för att kontrollera om this och other båda är icke-null och anropa en lambda om så är fallet. Används i implementationer.
type: docs
weight: 105
url: /sv/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Hjälpfunktion för att kontrollera om detta och **other** båda är icke-null och anropa en lambda om så är fallet. Används i implementationer.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Annat nullable-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | Annat nullable-värde att jämföra med. |
| f | const std::function\<**bool**()>\& | Lambda att anropa om både **this** och **other** inte är null. |
| default_if_both_are_null | **bool** | Returvärde om båda värdena är null. |

### Returvärde

false om antingen **this** eller **other** är null; **default_if_both_are_null** om båda är null; resultatet av **f**-anropet om båda inte är null.

## Se även

* Klass [Nullable](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)