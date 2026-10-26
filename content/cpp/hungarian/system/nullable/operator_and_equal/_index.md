---
title: operator&=()
second_title: Aspose.Slides C++ API referencia
description: Alkalmazza az operator&=() műveletet az aktuális objektum által képviselt értékre a megadott értéket jobboldali argumentumként használva.
type: docs
weight: 274
url: /hu/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) metódus


Alkalmazza a [operator&=()](./)-t az aktuális objektum által képviselt értékre a megadott értéket jobboldali argumentumként használva.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A sablonparaméter, amely lehetővé teszi a SFINAE működését. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | **bool** | Egy logikai érték, amely a [operator&=()](./) jobboldali értékeiként kerül felhasználásra az aktuális objektum által képviselt értékre alkalmazva. |

### Visszatérési érték

Az önre mutató referencia.

## Lásd még

* Osztály [Nullable](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)