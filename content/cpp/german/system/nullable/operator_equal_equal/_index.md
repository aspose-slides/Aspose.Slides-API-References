---
title: operator==()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der vom aktuellen Objekt dargestellte Wert null ist.
type: docs
weight: 118
url: /de/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const Methode


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert null ist.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Rückgabewert

True, wenn der vom aktuellen Objekt dargestellte Wert null ist, sonst - false

## Nullable::operator==(const T1\&) const Methode


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem angegebenen Wert entspricht.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des zu vergleichenden Werts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf den zu vergleichenden Wert |

### Rückgabewert

True, wenn der vom aktuellen Objekt dargestellte Wert dem angegebenen Wert entspricht, sonst - false

## Nullable::operator==(const Nullable\<T1\>\&) const Methode


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem Wert des angegebenen [Nullable](../) Objekts entspricht.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../) Objekts, mit dem verglichen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Eine konstante Referenz auf das [Nullable](../) Objekt, mit dem verglichen wird |

### Rückgabewert

True, wenn der vom aktuellen Objekt dargestellte Wert dem Wert des angegebenen [Nullable](../) Objekts entspricht, sonst - false

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)