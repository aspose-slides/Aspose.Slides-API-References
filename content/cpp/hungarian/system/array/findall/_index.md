---
title: FindAll()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaadja az összes olyan elemet, amely megfelel a megadott predikátum által definiált feltételeknek.
type: docs
weight: 664
url: /hu/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metódus


Visszaadja az összes olyan elemet, amely megfelel a megadott predikátum által definiált feltételeknek.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) amiben elemeket keres |
| match | [System::Predicate](../../predicate/)\<T\> | Egy predikátum, amely meghatározza a feltételeket a tömb elemeinek egyezéséhez |

### Visszatérési érték

Egy [Array](../) tartalmazza az összes elemet, amely megfelel a megadott predikátum által definiált feltételeknek, ha megtalálja; egyébként egy üres [Array](../).

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Osztály [Array](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)