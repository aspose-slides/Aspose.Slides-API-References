---
title: Find()
second_title: Aspose.Slides for C++ API referenciája
description: Megkeresi a megadott tömbben az első elemet, amely megfelel a megadott predikátum feltételeinek.
type: docs
weight: 651
url: /hu/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) metódus

Megkeresi a megadott tömbben az első elemet, amely megfelel a megadott predikátum feltételeinek.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) egy elem kereséséhez |
| match | [System::Predicate](../../predicate/)\<T\> | Egy predikátum, amely meghatározza a tömb elemek egyezésének feltételeit |

### Return Value

Az első elem másolata a tömbben, amely megfelel a predikátum által meghatározott feltételeknek, egyébként a T típusú alapértelmezett érték.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)