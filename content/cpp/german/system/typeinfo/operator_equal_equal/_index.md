---
title: operator==()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob das aktuelle und das angegebene TypeInfo-Objekt gleich sind.
type: docs
weight: 443
url: /de/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const Methode

Bestimmt, ob das aktuelle und das angegebene [TypeInfo](../) Objekt gleich sind.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Das [TypeInfo](../) Objekt zum Vergleich |

### Rückgabewert

True if the objects' hashes are equal, otherwise - false

## TypeInfo::operator==(std::nullptr_t) const Methode

Bestimmt, ob das aktuelle [TypeInfo](../) Objekt ein Null-Objekt ist, d.h. keinen Typ darstellt.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Rückgabewert

True if the current [TypeInfo](../) object is a null-object, otherwise - false

## Siehe auch

* Klasse [TypeInfo](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)