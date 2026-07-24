---
title: DateTime()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Instanz, die den kleinstmöglichen Datum- und Uhrzeitwert darstellt, der MinValue entspricht.
type: docs
weight: 1
url: /de/system/datetime/datetime/
---
## DateTime::DateTime() Konstruktor


Erstellt eine Instanz, die den kleinstmöglichen Datum- und Uhrzeitwert darstellt, der MinValue entspricht.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month** und **day** angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month** und **day** im angegebenen Kalender angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Der Kalender, der zum Interpretieren des angegebenen **year**, **month** und **day** verwendet wird. |

## DateTime::DateTime(int, int, int, int, int, int) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month**, **day**, **hour**, **minute** und **second** angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| hour | int | Die **hour** des **day**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| minute | int | Die **minute** der **hour**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| second | int | Die **second** der **minute**, die von der zu konstruierenden Instanz dargestellt werden soll. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month**, **day**, **hour**, **minute** und **second** angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| hour | int | Die **hour** des **day**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| minute | int | Die **minute** der **hour**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| second | int | Die **second** der **minute**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| kind | [DateTimeKind](../../datetimekind/) | Der Wert, der angibt, ob die übergebenen Datums- und Uhrzeitparameter eine lokale Zeit, UTC-Zeit oder weder noch angeben. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month**, **day**, **hour**, **minute** und **second** im angegebenen Kalender angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| hour | int | Die **hour** des **day**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| minute | int | Die **minute** der **hour**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| second | int | Die **second** der **minute**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Der Kalender, der zum Interpretieren des angegebenen **year**, **month** und **day** verwendet wird. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month**, **day**, **hour**, **minute**, **second** und **millisecond** angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| hour | int | Die **hour** des **day**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| minute | int | Die **minute** der **hour**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| second | int | Die **second** der **minute**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| millisecond | int | Die **millisecond** der **second**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| kind | [DateTimeKind](../../datetimekind/) | Der Wert, der angibt, ob die übergebenen Datums- und Uhrzeitparameter eine lokale Zeit, UTC-Zeit oder weder noch angeben. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als bestimmtes **year**, **month**, **day**, **hour**, **minute**, **second** und **millisecond** im angegebenen Kalender angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Das **year**, das von der zu konstruierenden Instanz dargestellt werden soll. |
| month | int | Der **month** des **year**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| day | int | Der **day** des **month**, der von der zu konstruierenden Instanz dargestellt werden soll. |
| hour | int | Die **hour** des **day**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| minute | int | Die **minute** der **hour**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| second | int | Die **second** der **minute**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| millisecond | int | Die **millisecond** der **second**, die von der zu konstruierenden Instanz dargestellt werden soll. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Der Wert, der angibt, ob die übergebenen Datums- und Uhrzeitparameter eine lokale Zeit, UTC-Zeit oder weder noch angeben. |
| calendar | [DateTimeKind](../../datetimekind/) | Der Kalender, der zum Interpretieren des angegebenen **year**, **month** und **day** verwendet wird. |

## DateTime::DateTime(int64_t, DateTimeKind) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als Anzahl von **ticks** angegeben ist.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ticks | **int64_t** | Die Anzahl von 100-ns-Intervallen, die seit dem 1. Januar 0001 00:00:00.000 im Gregorianischen Kalender vergangen sind. |
| kind | [DateTimeKind](../../datetimekind/) | Der Wert, der angibt, ob der **ticks**-Parameter eine lokale Zeit, UTC-Zeit oder weder noch angibt. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) Konstruktor


Erstellt eine Instanz, die einen Datum- und Uhrzeitwert darstellt, der als Anzahl von **ticks** angegeben ist. FÜR INTERNEN GEBRAUCH.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ticks | **int64_t** | Die Anzahl von 100-ns-Intervallen, die seit dem 1. Januar 0001 00:00:00 im Gregorianischen Kalender vergangen sind. |
| kind | [DateTimeKind](../../datetimekind/) | Der Wert, der angibt, ob der **ticks**-Parameter eine lokale Zeit, UTC-Zeit oder weder noch angibt. |
| is_ambiguous_local_dst | **bool** | Wahr, wenn das angegebene Datum und die Uhrzeit mehrdeutig sind und mehreren UTC-Zeitpunkten zugeordnet werden können. |

## DateTime::DateTime(const DateTime\&) Konstruktor


Kopiert eine Instanz.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Eine Instanz der Klasse [DateTime](../), aus der das dargestellte Datum- und Uhrzeitwert kopiert wird. |

## Siehe auch

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [DateTime](../)
* Klasse [Calendar](../../../system.globalization/calendar/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)