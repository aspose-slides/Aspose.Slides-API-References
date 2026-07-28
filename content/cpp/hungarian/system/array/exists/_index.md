---
title: Exists()
second_title: Aspose.Slides C++ API-referencia
description: Meghatározza, hogy a megadott Array objektum tartalmaz-e egy olyan elemet, amely megfelel a megadott predikátum követelményeinek.
type: docs
weight: 781
url: /hu/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) method


Megállapítja, hogy a megadott [Array](../) objektum tartalmaz-e egy olyan elemet, amely megfelel a megadott predikátum követelményeinek.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | A tömb, amelyben az elemet keressük |
| match | std::function\<**bool**(T)> | Függvényobjektum, amely meghatározza a követelményeket és ellenőrzi, hogy az elem megfelel-e nekik |

### Visszatérési érték

Igaz, ha a **arr** tartalmaz egy olyan elemet, amely megfelel a **match** által meghatározott követelményeknek

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [Array](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)