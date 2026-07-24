---
title: operator=()
second_title: Aspose.Slides für C++ API-Referenz
description: Weist dem aktuellen Objekt einen Nullwert zu.
type: docs
weight: 14
url: /de/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) Methode

Weist dem aktuellen Objekt einen Nullwert zu.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Rückgabewert

Ein [Nullable](../) Objekt, das einen Nullwert darstellt.

## Nullable::operator=(const T1\&) Methode

Ersetzt den derzeit vom Objekt repräsentierten Wert durch den angegebenen.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| Der | Typ des neuen Wertes, der vom aktuellen Objekt repräsentiert werden soll |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const T1\& | Der neue Wert, der vom aktuellen Objekt repräsentiert werden soll |

### Rückgabewert

Eine Referenz auf das Objekt selbst

## Nullable::operator=(const Nullable\<T1\>\&) Methode

Ersetzt den derzeit vom Objekt repräsentierten Wert durch den angegebenen.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| Der | Typ des neuen Wertes, der vom aktuellen Objekt repräsentiert werden soll |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Der neue Wert, der vom aktuellen Objekt repräsentiert werden soll |

### Rückgabewert

Eine Referenz auf das Objekt selbst

## Siehe auch

* Klasse [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)