---
title: operator>=()
second_title: Aspose.Slides for C++ API referencia
description: Megállapítja, hogy a jelenlegi objektum a dátum- és időértéket képviseli-e, amely későbbi vagy megegyezik a megadott DateTimeOffset objektummal reprezentált értékkel.
type: docs
weight: 599
url: /hu/system/datetimeoffset/operator_greater_equal/
---
## DateTimeOffset::operator>=(const DateTimeOffset\&) const metódus

Megállapítja, hogy a jelenlegi objektum a dátum és idő értéket képviseli-e, amely későbbi vagy megegyező a megadott [DateTimeOffset](../) objektummal.

```cpp
bool System::DateTimeOffset::operator>=(const DateTimeOffset &other) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | A [DateTimeOffset](../) objektum, amellyel a jelenlegi objektumot összehasonlítják |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt dátum és idő érték későbbi vagy megegyezik a **other** által képviselt értékkel, egyébként - hamis

## DateTimeOffset::operator>=(std::nullptr_t) const metódus

```cpp
constexpr bool System::DateTimeOffset::operator>=(std::nullptr_t) const
```

## Lásd még

* Osztály [DateTimeOffset](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)