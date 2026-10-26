---
title: DateTimeOffset()
second_title: Référence API Aspose.Slides pour C++
description: Constructeur par défaut.
type: docs
weight: 1
url: /fr/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructeur


Constructeur par défaut.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) constructeur


Constructeur.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) constructeur


Constructeur.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | Nombre de ticks. |
| offset | [TimeSpan](../../timespan/) | Décalage horaire par rapport à UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) constructeur


Constructeur.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure. |
| offset | [TimeSpan](../../timespan/) | Décalage horaire par rapport à UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) constructeur


Constructeur.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | Année (1 à 9999). |
| month | int | Mois (1 à 12). |
| day | int | Jour (1 au nombre de jours du mois). |
| hour | int | Heure (0 à 23). |
| minute | int | Minute (0 à 59). |
| second | int | Seconde (0 à 59). |
| offset | [TimeSpan](../../timespan/) | Décalage horaire par rapport à UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) constructeur


Constructeur.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | Année (1 à 9999). |
| month | int | Mois (1 à 12). |
| day | int | Jour (1 au nombre de jours du mois). |
| hour | int | Heure (0 à 23). |
| minute | int | Minute (0 à 59). |
| second | int | Seconde (0 à 59). |
| millisecond | int | Milliseconde (0 à 999). |
| offset | [TimeSpan](../../timespan/) | Décalage horaire par rapport à UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) constructeur


Constructeur.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | Année. |
| month | int | Mois (1 à 12). |
| day | int | Jour (1 au nombre de jours du mois). |
| hour | int | Heure (0 à 23). |
| minute | int | Minute (0 à 59). |
| second | int | Seconde (0 à 59). |
| millisecond | int | Milliseconde (0 à 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Calendrier utilisé pour interpréter l'année, le mois et le jour. |
| offset | [TimeSpan](../../timespan/) | Décalage horaire par rapport à UTC. |

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTimeOffset](../)
* Classe [DateTime](../../datetime/)
* Classe [TimeSpan](../../timespan/)
* Classe [Calendar](../../../system.globalization/calendar/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)