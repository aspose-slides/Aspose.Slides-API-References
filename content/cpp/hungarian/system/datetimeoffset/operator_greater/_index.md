---
title: operator>()
second_title: Aspose.Slides for C++ API Referencia
description: Megállapítja, hogy az aktuális objektum a dátum- és időértéket képviseli-e, amely későbbi, mint a megadott DateTimeOffset objektum által képviselt érték.
type: docs
weight: 573
url: /hu/system/datetimeoffset/operator_greater/
---
## DateTimeOffset::operator>(const DateTimeOffset\&) const metódus


Meghatározza, hogy az aktuális objektum a dátum- és időértéket képviseli-e, amely későbbi, mint a megadott [DateTimeOffset](../) objektummal reprezentált érték.

```cpp
bool System::DateTimeOffset::operator>(const DateTimeOffset &other) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | A [DateTimeOffset](../) objektum, amellyel az aktuális objektumot össze kell hasonlítani |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt dátum és időérték későbbi, mint a **other** által képviselt érték, egyébként - hamis

## DateTimeOffset::operator>(std::nullptr_t) const metódus




```cpp
constexpr bool System::DateTimeOffset::operator>(std::nullptr_t) const
```

## Lásd még

* Osztály [DateTimeOffset](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)