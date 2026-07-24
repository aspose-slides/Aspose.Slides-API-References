---
title: operator<=()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt immer false zurück.
type: docs
weight: 196
url: /de/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const Methode

Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const Methode

Bestimmt, ob der durch das aktuelle Objekt dargestellte Wert kleiner oder gleich dem angegebenen Wert ist, indem [operator<=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | The type of the value to compare with |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### Rückgabewert

True if the value represented by the current object is less or equal to the specified value, otherwise - false

## Nullable::operator<=(const Nullable\<T1\>\&) const Methode

Bestimmt, ob der durch das aktuelle Objekt dargestellte Wert kleiner oder gleich dem von dem angegebenen [Nullable](../)-Objekt dargestellten Wert ist, indem [operator<=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### Rückgabewert

True if the value represented by the current object is less or equal to the value represented by the specified [Nullable](../) object, otherwise - false

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)