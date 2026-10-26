---
title: operator!=()
second_title: Aspose.Slides for C++ API hivatkozás
description: Megállapítja, hogy a jelenlegi és a megadott TypeInfo objektumok nem egyenlőek.
type: docs
weight: 456
url: /hu/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const metódus

Megállapítja, hogy a jelenlegi és a megadott [TypeInfo](../) objektumok nem egyenlőek.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | A [TypeInfo](../) objektum, amellyel össze kell hasonlítani |

### Visszatérési érték

Igaz, ha az objektumok hash értékei nem egyenlőek, egyébként – hamis

## TypeInfo::operator!=(std::nullptr_t) const metódus

Megállapítja, hogy a jelenlegi [TypeInfo](../) objektum nem null-objektum-e, vagyis reprezentál egy típust.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### Visszatérési érték

Igaz, ha a jelenlegi [TypeInfo](../) objektum nem null-objektum, egyébként – hamis

## Lásd még

* Osztály [TypeInfo](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)