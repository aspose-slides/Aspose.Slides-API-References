---
title: Exists()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Określa, czy określony obiekt Array zawiera element spełniający wymagania określonego predykatu.
type: docs
weight: 781
url: /pl/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) metoda


Określa, czy podany obiekt [Array](../) zawiera element spełniający wymagania określonego predykatu.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Tablica, w której należy szukać elementu |
| match | std::function\<**bool**(T)> | Obiekt funkcyjny definiujący wymagania i sprawdzający, czy element je spełnia |

### Wartość zwracana

Prawda, jeśli **arr** zawiera element spełniający wymagania określone przez **match**

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)