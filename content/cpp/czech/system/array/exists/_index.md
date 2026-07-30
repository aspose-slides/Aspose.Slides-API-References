---
title: Exists()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda zadaný objekt Array obsahuje prvek, který splňuje požadavky zadaného predikátu.
type: docs
weight: 781
url: /cs/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) metoda

Určuje, zda daný objekt [Array](../) obsahuje prvek, který splňuje požadavky zadaného predikátu.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Pole, ve kterém se hledá prvek |
| match | std::function\<**bool**(T)> | Objekt funkce, který definuje požadavky a kontroluje, zda prvek splňuje tyto požadavky |

### Návratová hodnota

True pokud **arr** obsahuje prvek, který splňuje požadavky definované **match**

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)