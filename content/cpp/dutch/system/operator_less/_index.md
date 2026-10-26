---
title: operator<()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 2094
url: /nl/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) function


Geeft altijd false terug.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) function


Bepaalt of de opgegeven waarde kleiner is dan de waarde die wordt weergegeven door het opgegeven [Nullable](../nullable/)-object door [operator<()](./) op deze waarden toe te passen.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de eerste vergelijkingswaarde |
| T2 | Het onderliggende type van het [Nullable](../nullable/)-object dat de tweede vergelijkingswaarde vertegenwoordigt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| some | const T1\& | Een constante referentie naar de waarde die als eerste vergelijkingswaarde moet worden gebruikt |
| other | const [Nullable](../nullable/)\<T2\>\& | Een constante referentie naar het [Nullable](../nullable/)-object waarvan de weergegeven waarde als tweede vergelijkingswaarde moet worden gebruikt |

### Retourwaarde

True als de eerste vergelijkingswaarde kleiner is dan de tweede vergelijkingswaarde, anders - false

## System::operator<(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Zie ook

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)