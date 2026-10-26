---
title: operator==()
second_title: Aspose.Slides C++ API Referencia
description: Megállapítja, hogy a jelenlegi és a megadott TypeInfo objektumok egyenlőek-e.
type: docs
weight: 443
url: /hu/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const metódus

Megállapítja, hogy a jelenlegi és a megadott [TypeInfo](../) objektumok egyenlőek-e.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | A [TypeInfo](../) objektum, amellyel összehasonlítandó |

### Visszatérési érték

Igaz, ha az objektumok hash értékei egyenlőek, egyébként - hamis

## TypeInfo::operator==(std::nullptr_t) const metódus

Megállapítja, hogy a jelenlegi [TypeInfo](../) objektum egy null-objektum, azaz nem képvisel semmilyen típust.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Visszatérési érték

Igaz, ha a jelenlegi [TypeInfo](../) objektum egy null-objektum, egyébként - hamis

## Lásd még

* Osztály [TypeInfo](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)