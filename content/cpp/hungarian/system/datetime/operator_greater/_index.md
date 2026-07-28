---
title: operator>()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy az aktuális objektum a megadott DateTime objektum által képviselt értéknél későbbi dátum- és időértéket képvisel-e.
type: docs
weight: 612
url: /hu/system/datetime/operator_greater/
---
## DateTime::operator>(DateTime) const metódus

Meghatározza, hogy az aktuális objektum a megadott [DateTime](../) objektum által képviselt értéknél későbbi dátum- és időértéket képvisel-e.

```cpp
constexpr bool System::DateTime::operator>(DateTime other) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | [DateTime](../) | A [DateTime](../) objektum, amelyhez az aktuális objektumot hasonlítjuk |

### Visszatérési érték

Igaz, ha az aktuális objektum által képviselt dátum- és időérték későbbi, mint a **other** által képviselt érték, egyébként - false

## DateTime::operator>(std::nullptr_t) const metódus

```cpp
constexpr bool System::DateTime::operator>(std::nullptr_t) const
```

## Lásd még

* Osztály [DateTime](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)