---
title: DateTime()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een instantie die de kleinste mogelijke datum- en tijdwaarde vertegenwoordigt die gelijk is aan MinValue.
type: docs
weight: 1
url: /nl/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Construeert een instantie die de kleinst mogelijke datum- en tijdwaarde vertegenwoordigt die gelijk is aan MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand en dag.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand en dag in de opgegeven kalender.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | De kalender die wordt gebruikt om het opgegeven **year**, **month** en **day** te interpreteren. |

## DateTime::DateTime(int, int, int, int, int, int) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut en seconde.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |
| hour | int | Het uur van de **day** die door de te construeren instantie wordt weergegeven. |
| minute | int | De minuut van het **hour** die door de te construeren instantie wordt weergegeven. |
| second | int | De seconde van de **minute** die moet worden vertegenwoordigd door de instantie die wordt geconstrueerd. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut en seconde.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |
| hour | int | Het uur van de **day** die door de te construeren instantie wordt weergegeven. |
| minute | int | De minuut van het **hour** die door de te construeren instantie wordt weergegeven. |
| second | int | De seconde van de **minute** die moet worden vertegenwoordigd door de instantie die wordt geconstrueerd. |
| kind | [DateTimeKind](../../datetimekind/) | De waarde die aangeeft of de opgegeven datum- en tijdparameters een lokale tijd, UTC-tijd of geen van beide specificeren. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut en seconde in de opgegeven kalender.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |
| hour | int | Het uur van de **day** die door de te construeren instantie wordt weergegeven. |
| minute | int | De minuut van het **hour** die door de te construeren instantie wordt weergegeven. |
| second | int | De seconde van de **minute** die moet worden vertegenwoordigd door de instantie die wordt geconstrueerd. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | De kalender die wordt gebruikt om het opgegeven **year**, **month** en **day** te interpreteren. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut, seconde en milliseconde.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |
| hour | int | Het uur van de **day** die door de te construeren instantie wordt weergegeven. |
| minute | int | De minuut van het **hour** die door de te construeren instantie wordt weergegeven. |
| second | int | De seconde van de **minute** die moet worden vertegenwoordigd door de instantie die wordt geconstrueerd. |
| millisecond | int | De milliseconde van de **second** die door de te construeren instantie wordt weergegeven. |
| kind | [DateTimeKind](../../datetimekind/) | De waarde die aangeeft of de opgegeven datum- en tijdparameters een lokale tijd, UTC-tijd of geen van beide specificeren. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een specifiek jaar, maand, dag, uur, minuut, seconde en milliseconde in de opgegeven kalender.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Het jaar dat door de te construeren instantie wordt weergegeven. |
| month | int | De maand van het **year** die door de te construeren instantie wordt weergegeven. |
| day | int | De dag van de **month** die door de te construeren instantie wordt weergegeven. |
| hour | int | Het uur van de **day** die door de te construeren instantie wordt weergegeven. |
| minute | int | De minuut van het **hour** die door de te construeren instantie wordt weergegeven. |
| second | int | De seconde van de **minute** die moet worden vertegenwoordigd door de instantie die wordt geconstrueerd. |
| millisecond | int | De milliseconde van de **second** die door de te construeren instantie wordt weergegeven. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | De waarde die aangeeft of de opgegeven datum- en tijdparameters een lokale tijd, UTC-tijd of geen van beide specificeren. |
| calendar | [DateTimeKind](../../datetimekind/) | De kalender die wordt gebruikt om het opgegeven **year**, **month** en **day** te interpreteren. |

## DateTime::DateTime(int64_t, DateTimeKind) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een aantal ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ticks | **int64_t** | Het aantal 100-ns-intervallen dat is verstreken sinds 1 januari 0001 00:00:00.000 in de Georgische kalender. |
| kind | [DateTimeKind](../../datetimekind/) | De waarde die aangeeft of de **ticks**-parameter een lokale tijd, UTC-tijd of geen van beide specificeert. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor


Construeert een instantie die een datum- en tijdwaarde vertegenwoordigt die is opgegeven als een aantal ticks. VOOR INTERN GEBRUIK.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ticks | **int64_t** | Het aantal 100-ns-intervallen dat is verstreken sinds 1 januari 0001 00:00:00.000 in de Georgische kalender. |
| kind | [DateTimeKind](../../datetimekind/) | De waarde die aangeeft of de **ticks**-parameter een lokale tijd, UTC-tijd of geen van beide specificeert. |
| is_ambiguous_local_dst | **bool** | True als de opgegeven datum en tijd dubbelzinnig is en aan vele UTC-tijden kan worden gekoppeld. |

## DateTime::DateTime(const DateTime\&) constructor


Kopieert een instantie.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Een instantie van de [DateTime](../)-klasse waarvan de vertegenwoordigde datum- en tijdwaarde moet worden gekopieerd. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)