---
title: operator>=()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 2133
url: /de/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) function


Gibt immer false zurück.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) function


Bestimmt, ob der angegebene Wert größer oder gleich dem Wert ist, der durch das angegebene [Nullable](../nullable/)-Objekt dargestellt wird, indem [operator>=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des ersten Vergleichswerts |
| T2 | Der zugrunde liegende Typ des [Nullable](../nullable/)-Objekts, das den zweiten Vergleichswert darstellt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| some | const T1\& | Eine konstante Referenz auf den Wert, der als erster Vergleichswert verwendet werden soll |
| other | const [Nullable](../nullable/)\<T2\>\& | Eine konstante Referenz auf das [Nullable](../nullable/)-Objekt, dessen dargestellter Wert als zweiter Vergleichswert verwendet werden soll |

### Rückgabewert

True, wenn der erste Vergleichswert größer oder gleich dem zweiten Vergleichswert ist, sonst - false

## System::operator>=(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Siehe auch

* Klasse [DateTime](../datetime/)
* Klasse [DateTimeOffset](../datetimeoffset/)
* Klasse [Nullable](../nullable/)
* Klasse [TimeSpan](../timespan/)
* Struktur [IsNullable](../isnullable/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)