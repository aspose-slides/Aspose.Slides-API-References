---
title: Equals()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen Nullable-Objekt entspricht.
type: docs
weight: 131
url: /de/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const Methode

Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen [Nullable](../) Objekt entspricht.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../) Objekts, mit dem verglichen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf das [Nullable](../) Objekt, mit dem verglichen wird |

### Rückgabewert

True, wenn der vom aktuellen Objekt dargestellte Wert dem vom angegebenen [Nullable](../) Objekt entspricht, andernfalls - false

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)