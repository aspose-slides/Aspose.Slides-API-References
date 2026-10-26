---
title: operator>=()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt immer false zurück.
type: docs
weight: 183
url: /de/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const Methode


Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Rückgabewert

Immer - false

## Nullable::operator>=(const T1\&) const Methode


Bestimmt, ob der durch das aktuelle Objekt dargestellte Wert größer oder gleich dem durch das angegebene Objekt dargestellten Wert ist, indem [operator>=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrundeliegende Typ des Wertes, mit dem der durch das aktuelle Objekt dargestellte Wert verglichen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf ein Objekt, mit dem das aktuelle Objekt verglichen wird |

### Rückgabewert

True, wenn der durch das aktuelle Objekt dargestellte Wert größer oder gleich dem durch das angegebene Objekt dargestellten Wert ist, sonst - false

## Nullable::operator>=(const Nullable\<T1\>\&) const Methode


Bestimmt, ob der durch das aktuelle Objekt dargestellte Wert größer oder gleich dem durch das angegebene [Nullable](../)-Objekt dargestellten Wert ist, indem [operator>=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrundeliegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### Rückgabewert

True, wenn der durch das aktuelle Objekt dargestellte Wert größer oder gleich dem durch das angegebene [Nullable](../)-Objekt dargestellten Wert ist, sonst - false

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)