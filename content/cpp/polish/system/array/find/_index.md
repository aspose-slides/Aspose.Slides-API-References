---
title: Find()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Wyszukuje pierwszy element w określonej tablicy, który spełnia warunki określonego predykatu.
type: docs
weight: 651
url: /pl/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda

Wyszukuje pierwszy element w określonej tablicy, który spełnia warunki określonego predykatu.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) do wyszukania elementu w |
| match | [System::Predicate](../../predicate/)\<T\> | Predykat określający warunki, którym muszą odpowiadać elementy tablicy |

### Wartość zwracana

Kopia pierwszego elementu w tablicy, który spełnia warunki określone przez predykat, w przeciwnym razie domyślna wartość typu T

## Zobacz także

* Definicja typu [ArrayPtr](../../arrayptr/)
* Definicja typu [Predicate](../../predicate/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)