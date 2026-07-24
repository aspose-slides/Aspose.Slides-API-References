---
title: operator+()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine standardmäßig konstruierte Instanz der Klasse Nullable<T> zurück.
type: docs
weight: 209
url: /de/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const Methode

Gibt eine standardmäßig konstruierte Instanz der Klasse Nullable<T> zurück.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const Methode

Addiert nullable- und nicht-nullable-Werte.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des rechten Operanden. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Wert, der addiert wird. |

### Rückgabewert

Ergebnis der Addition.

## Nullable::operator+(const Nullable\<T1\>\&) const Methode

Addiert nullable-Werte.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des rechten Operanden. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Wert, der addiert wird. |

### Rückgabewert

Ergebnis der Addition.

## Siehe auch

* Klasse [Nullable](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)