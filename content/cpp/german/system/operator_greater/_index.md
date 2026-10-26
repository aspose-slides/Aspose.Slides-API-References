---
title: operator>()
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 2120
url: /de/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) Funktion




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) Funktion




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) Funktion


Gibt immer false zurück.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) Funktion


Ermittelt, ob der angegebene Wert größer ist als der vom angegebenen [Nullable](../nullable/)-Objekt repräsentierte Wert, indem [operator>()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des ersten Vergleichswerts |
| T2 | Der zugrundeliegende Typ des [Nullable](../nullable/)-Objekts, das den zweiten Vergleichswert darstellt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| some | const T1\& | Eine konstante Referenz auf den Wert, der als erster Vergleichswert verwendet werden soll |
| other | const [Nullable](../nullable/)\<T2\>\& | Eine konstante Referenz auf das [Nullable](../nullable/)-Objekt, dessen repräsentierter Wert als zweiter Vergleichswert verwendet werden soll |

### Rückgabewert

True, wenn der erste Vergleichswert größer als der zweite Vergleichswert ist, sonst false

## System::operator>(std::nullptr_t, TimeSpan) Funktion




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## Siehe auch

* Klasse [DateTime](../datetime/)
* Klasse [DateTimeOffset](../datetimeoffset/)
* Klasse [Nullable](../nullable/)
* Klasse [TimeSpan](../timespan/)
* Struktur [IsNullable](../isnullable/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)