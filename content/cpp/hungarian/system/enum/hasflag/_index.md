---
title: HasFlag()
second_title: Aspose.Slides for C++ API referencia
description: Megállapítja, hogy a megadott bitek be vannak-e állítva a megadott enum érték bitáris ábrázolásában.
type: docs
weight: 14
url: /hu/system/enum/hasflag/
---
## Enum::HasFlag(E, E) metódus


Determines if the specified bits are set in a bitary representation of the specified enum value.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | E | A tesztelendő enum érték |
| mask | E | Az a maszk, amellyel a value biteit ellenőrizzük |

### Visszatérési érték

Igaz, ha a **mask**-ben beállított bitek szintén be vannak állítva a **value**-ban, egyébként - hamis

## Lásd még

* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)