---
title: TrueForAll()
second_title: Aspose.Slides dla C++ - referencja API
description: Określa, czy wszystkie elementy w podanej tablicy spełniają warunki określone przez podany predykat.
type: docs
weight: 677
url: /pl/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda

Określa, czy wszystkie elementy w podanej tablicy spełniają warunki zdefiniowane przez określony predykat.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elementy, które mają być dopasowane do warunków |
| match | [System::Predicate](../../predicate/)\<T\> | Predykat definiujący warunki, którym mają odpowiadać elementy tablicy |

### Wartość zwracana

true if all elements of the array arr satisfy the conditions defined by predicate match, otherwise false

## Zobacz także

* Definicja typu [ArrayPtr](../../arrayptr/)
* Definicja typu [Predicate](../../predicate/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)