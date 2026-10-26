---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Funkcja pomocnicza służąca do określenia, czy konkretna klasa posiada operator ==.
type: docs
weight: 235
url: /pl/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) funkcja

Funkcja pomocnicza określająca, czy dana klasa posiada operator ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ do sprawdzenia. |
| Dummy | Argument zastępczy dla magii SFINAE. |

### Wartość zwracana

Wartość std::true_type, jeśli operator == jest obecny, w przeciwnym razie false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) funkcja

Funkcja pomocnicza określająca, czy dana klasa posiada operator ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Wartość zwracana

Wartość std::true_type, jeśli operator == jest obecny, w przeciwnym razie false.

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic::Details](../)
* Biblioteka [Aspose.Slides](../../)