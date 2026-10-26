---
title: operator!=()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert nicht null ist.
type: docs
weight: 144
url: /de/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const Methode


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert nicht null ist.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### Rückgabewert

True, wenn der von dem aktuellen Objekt dargestellte Wert nicht null ist, sonst - false

## Nullable::operator!=(const T1\&) const Methode


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert nicht gleich dem angegebenen Wert ist.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des zu vergleichenden Wertes |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf den zu vergleichenden Wert |

### Rückgabewert

True, wenn der von dem aktuellen Objekt dargestellte Wert nicht gleich dem angegebenen Wert ist, sonst - false

## Nullable::operator!=(const Nullable\<T1\>\&) const Methode


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert nicht gleich dem von dem angegebenen [Nullable](../) Objekt dargestellten Wert ist.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../) Objekts, mit dem verglichen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Eine konstante Referenz auf das [Nullable](../) Objekt zum Vergleichen |

### Rückgabewert

True, wenn der von dem aktuellen Objekt dargestellte Wert nicht gleich dem von dem angegebenen [Nullable](../) Objekt dargestellten Wert ist, sonst - false

## Siehe auch

* Klasse [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)