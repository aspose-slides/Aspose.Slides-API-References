---
title: TrueForAll()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a megadott tömb összes eleme megfelel-e a megadott feltételeket meghatározó predikátumnak.
type: docs
weight: 677
url: /hu/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metódus


Megállapítja, hogy a megadott tömb összes eleme megfelel-e a megadott feltételt meghatározó predikátumnak.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elemek, amelyekkel a feltételeket kell egyeztetni |
| match | [System::Predicate](../../predicate/)\<T\> | Egy predikátum, amely meghatározza a feltételeket, amelyek ellenőrzése a tömb elemeire vonatkozik |

### Visszatérési érték

true, ha a(z) arr tömb összes eleme megfelel a match predikátum által meghatározott feltételeknek, egyébként false

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Típusdefiníció [Predicate](../../predicate/)
* Osztály [Array](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)