---
title: operator>()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt immer false zurück.
type: docs
weight: 157
url: /de/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const Methode

Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const Methode

Bestimmt, ob der durch das aktuelle Objekt dargestellte Wert größer ist als der angegebene Wert, indem [operator>()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des zu vergleichenden Werts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf den zu vergleichenden Wert |

### Rückgabewert

True, wenn der durch das aktuelle Objekt dargestellte Wert größer ist als der angegebene Wert, sonst - false

## Nullable::operator>(const Nullable\<T1\>\&) const Methode

Bestimmt, ob der durch das aktuelle Objekt dargestellte Wert größer ist als der durch das angegebene [Nullable](../) Objekt dargestellte Wert, indem [operator>()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../) Objekts, mit dem verglichen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Eine konstante Referenz auf das [Nullable](../) Objekt, mit dem verglichen wird |

### Rückgabewert

True, wenn der durch das aktuelle Objekt dargestellte Wert größer ist als der durch das angegebene [Nullable](../) Objekt dargestellte Wert, sonst - false

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)