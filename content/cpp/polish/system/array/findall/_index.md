---
title: FindAll()
second_title: Aspose.Slides dla C++ – referencja API
description: Pobiera wszystkie elementy, które spełniają warunki określone przez podany predykat.
type: docs
weight: 664
url: /pl/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metoda

Pobiera wszystkie elementy, które spełniają warunki określone przez podany predykat.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) do przeszukania elementów w |
| match | [System::Predicate](../../predicate/)\<T\> | Predykat definiujący warunki, według których dopasowywane są elementy tablicy |

### Wartość zwracana

Obiekt [Array](../) zawierający wszystkie elementy, które spełniają warunki określone przez podany predykat, jeśli zostaną znalezione; w przeciwnym razie pusty [Array](../).

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)