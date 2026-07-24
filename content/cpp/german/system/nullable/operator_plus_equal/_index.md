---
title: operator+=()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt das aktuelle Objekt zurück, sodass es einen Nullwert darstellt.
type: docs
weight: 235
url: /de/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) Methode

Setzt das aktuelle Objekt zurück, sodass es einen Nullwert darstellt.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Rückgabewert

Eine Kopie des Objekts selbst

## Nullable::operator+=(const T1\&) Methode

Wendet [operator+=()](./) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den angegebenen Wert als Rechtsseit-Argument.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des Wertes, der als Rechtswert von [operator+=()](./) verwendet wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf den Wert, der als Rechtswert des [operator+=()](./) verwendet wird, das auf den vom aktuellen Objekt dargestellten Wert angewendet wird. |

### Rückgabewert

Eine Referenz auf das Objekt selbst

## Nullable::operator+=(const Nullable\<T1\>\&) Methode

Wendet [operator+=()](./) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den Wert des angegebenen [Nullable](../)-Objekts als Rechtsseit-Argument.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ eines [Nullable](../)-Objekts, dessen dargestellter Wert als Rechtsseit-Argument von [operator+=()](./) verwendet wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, dessen dargestellter Wert als Rechtsseit-Argument des [operator+=()](./) verwendet wird, das auf den vom aktuellen Objekt dargestellten Wert angewendet wird. |

### Rückgabewert

Eine Referenz auf das Objekt selbst

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Bibliothek [Aspose.Slides](../../../)