---
title: Exists()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om det angivna Array-objektet innehåller ett element som uppfyller kraven för det angivna predikatet.
type: docs
weight: 781
url: /sv/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) metod


Avgör om det angivna [Array](../)-objektet innehåller ett element som uppfyller kraven för det angivna predikatet.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Arrayen att söka efter elementet i |
| match | std::function\<**bool**(T)> | Funktionsobjekt som definierar kraven och kontrollerar om ett element uppfyller dem |

### Returvärde

Sant om **arr** innehåller ett element som uppfyller kraven som definieras av **match**

## Se också

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)