---
title: operator|=()
second_title: Aspose.Slides C++ API Referencia
description: Alkalmazza az operator|=() függvényt az aktuális objektum által képviselt értékre, a megadott értéket jobb oldali argumentumként használva.
type: docs
weight: 261
url: /hu/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) metódus

Alkalmazza a(z) [operator|=()](./)-t az aktuális objektum által képviselt értékre, a megadott értéket jobb oldali argumentumként használva.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A sablonparaméter, amely lehetővé teszi az SFINAE működését. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | **bool** | Logikai érték, amelyet a [operator|=()](./) jobb oldalú értékeként használnak az aktuális objektum által képviselt értékre alkalmazva. |

### Visszatérési érték

Az önre mutató referencia.

## Lásd még

* Osztály [Nullable](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)