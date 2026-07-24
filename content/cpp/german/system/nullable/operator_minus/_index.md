---
title: operator-()
second_title: Aspose.Slides für C++ API-Referenz
description: Subtrahiert nullable und null-gezeigte Werte.
type: docs
weight: 222
url: /de/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const Methode

Subtrahiert nullable- und null-gezeigte Werte.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des rechten Operanden, sollte nullptr_t sein. |

### Rückgabewert

Leeres [Nullable](../)-Objekt.

## Nullable::operator-(const T1&) const Methode

Subtrahiert nullable- und nicht-nullable Werte.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des rechten Operanden. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1& | Wert zum Subtrahieren. |

### Rückgabewert

Subtraktionsergebnis.

## Nullable::operator-(const Nullable<T1>&) const Methode

Subtrahiert nullable Werte.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des rechten Operanden. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)<T1>& | Wert zum Subtrahieren. |

### Rückgabewert

Subtraktionsergebnis.

## Siehe auch

* Klasse [Nullable](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)