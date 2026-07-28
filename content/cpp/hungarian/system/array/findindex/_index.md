---
title: FindIndex()
second_title: Aspose.Slides C++ API hivatkozás
description: Megkeresi a megadott tömbben az első elemet, amely megfelel a megadott predikátum feltételeinek.
type: docs
weight: 638
url: /hu/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) metódus

Megkeresi az első elemet a megadott tömbben, amely megfelel a megadott predikátum feltételeinek.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elem kereséséhez |
| match | [System::Predicate](../../predicate/)\<T\> | Egy predikátum, amely meghatározza a tömb elemeinek illesztési feltételeit |

### Visszatérési érték

Az első elem indexe a tömbben, amely megfelel a predikátum által meghatározott feltételeknek, egyébként -1

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Osztály [Array](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)