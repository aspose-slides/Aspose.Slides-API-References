---
title: TimeSpan()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een TimeSpan object dat een tijdsinterval van nul vertegenwoordigt.
type: docs
weight: 1
url: /nl/system/timespan/timespan/
---
## TimeSpan::TimeSpan() constructor


Construeert een [TimeSpan](../) object dat een tijdsinterval van nul vertegenwoordigt.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) constructor


Construeert een instantie van de klasse [TimeSpan](../) die het opgegeven tijdsinterval vertegenwoordigt.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ticks | **int64_t** | Het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd, uitgedrukt als het aantal intervallen van 100 nanoseconden. |

## TimeSpan::TimeSpan(int, int, int) constructor


Construeert een instantie van de klasse [TimeSpan](../) die het tijdsinterval vertegenwoordigt dat gelijk is aan de som van het opgegeven aantal uren, minuten en seconden.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hours | int | Het aantal uren in het uren-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |
| minutes | int | Het aantal minuten in het minuten-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |
| seconds | int | Het aantal seconden in het seconden-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |

## TimeSpan::TimeSpan(int, int, int, int, int) constructor


Construeert een instantie van de klasse [TimeSpan](../) die het tijdsinterval vertegenwoordigt dat gelijk is aan de som van het opgegeven aantal uren, minuten, seconden en milliseconden.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| days | int | Het aantal dagen in het dagen-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |
| hours | int | Het aantal uren in het uren-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |
| minutes | int | Het aantal minuten in het minuten-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |
| seconds | int | Het aantal seconden in het seconden-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |
| milliseconds | int | Het aantal milliseconden in het milliseconden-component van het tijdsinterval dat door de te construeren instantie wordt vertegenwoordigd |

## TimeSpan::TimeSpan(const TimeSpan\&) constructor


Construeert een [TimeSpan](../) object dat het tijdsinterval vertegenwoordigt dat gelijk is aan het tijdsinterval van het opgegeven [TimeSpan](../) object.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Zie ook

* Klasse [TimeSpan](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)