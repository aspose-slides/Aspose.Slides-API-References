---
title: operator-=()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt eine Instanz der Klasse Nullable zurück, die einen Nullwert darstellt.
type: docs
weight: 248
url: /de/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) Methode


Gibt eine Instanz der Klasse [Nullable](../) zurück, die einen Nullwert darstellt.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) Methode


Wendet [operator-=()](./) auf den vom aktuellen Objekt repräsentierten Wert an und verwendet den angegebenen Wert als rechten Operanden.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T1 | Der Typ des Wertes, der als rechter Operand von [operator-=()](./) verwendet wird |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf den Wert, der als rechter Operand des [operator-=()](./) verwendet wird, der auf den vom aktuellen Objekt repräsentierten Wert angewendet wird. |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt

## Nullable::operator-=(const Nullable\<T1\>\&) Methode


Wendet [operator-=()](./) auf den vom aktuellen Objekt repräsentierten Wert an und verwendet den von dem angegebenen [Nullable](../)-Objekt repräsentierten Wert als rechten Operanden.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T1 | Der zugrunde liegende Typ eines [Nullable](../)-Objekts, dessen repräsentierter Wert als rechter Operand von [operator-=()](./) verwendet wird |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Eine konstante Referenz auf ein [Nullable](../)-Objekt, dessen repräsentierter Wert als rechter Operand des [operator-=()](./) verwendet wird, der auf den vom aktuellen Objekt repräsentierten Wert angewendet wird. |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)