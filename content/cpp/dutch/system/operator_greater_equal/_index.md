---
title: operator>=()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 2133
url: /nl/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) functie

```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```
## System::operator>=(std::nullptr_t, const DateTimeOffset\&) functie

```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```
## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) functie

Geeft altijd false terug.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```
## System::operator>=(const T1\&, const Nullable\<T2\>\&) functie

Bepaalt of de opgegeven waarde groter of gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](../nullable/)-object door [operator>=()](./) op deze waarden toe te passen.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de eerste vergelijkingswaarde |
| T2 | Het onderliggende type van het [Nullable](../nullable/)-object dat de tweede vergelijkingswaarde vertegenwoordigt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| some | const T1\& | Een constante referentie naar de waarde die moet worden gebruikt als de eerste vergelijkingswaarde |
| other | const [Nullable](../nullable/)\<T2\>\& | Een constante referentie naar het [Nullable](../nullable/)-object waarvan de vertegenwoordigde waarde moet worden gebruikt als de tweede vergelijkingswaarde |

### Retourwaarde

True als de eerste vergelijkingswaarde groter of gelijk is aan de tweede vergelijkingswaarde, anders - false

## System::operator>=(std::nullptr_t, TimeSpan) functie

```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```
## Zie ook

* Klasse [DateTime](../datetime/)
* Klasse [DateTimeOffset](../datetimeoffset/)
* Klasse [Nullable](../nullable/)
* Klasse [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)