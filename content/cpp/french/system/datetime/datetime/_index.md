---
title: DateTime()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une instance qui représente la valeur de date et d'heure la plus petite possible, égale à MinValue.
type: docs
weight: 1
url: /fr/system/datetime/datetime/
---
## DateTime::DateTime() constructeur

Construit une instance qui représente la valeur de date et d'heure la plus petite possible, égale à MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois et un jour particuliers.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois et un jour particuliers dans le calendrier spécifié.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Le calendrier utilisé pour interpréter l'**année**, le **mois** et le **jour** spécifiés. |

## DateTime::DateTime(int, int, int, int, int, int) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois, un jour, une heure, une minute et une seconde particulières.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |
| hour | int | L'heure du **jour** à représenter par l'instance en cours de construction. |
| minute | int | La minute de l'**heure** à représenter par l'instance en cours de construction. |
| second | int | La seconde de la **minute** à être représentée par l'instance en cours de construction. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois, un jour, une heure, une minute et une seconde particulières.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |
| hour | int | L'heure du **jour** à représenter par l'instance en cours de construction. |
| minute | int | La minute de l'**heure** à représenter par l'instance en cours de construction. |
| second | int | La seconde de la **minute** à être représentée par l'instance en cours de construction. |
| kind | [DateTimeKind](../../datetimekind/) | La valeur qui indique si les paramètres de date et d'heure fournis spécifient une heure locale, une heure UTC ou aucune des deux. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois, un jour, une heure, une minute et une seconde particulières dans le calendrier spécifié.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |
| hour | int | L'heure du **jour** à représenter par l'instance en cours de construction. |
| minute | int | La minute de l'**heure** à représenter par l'instance en cours de construction. |
| second | int | La seconde de la **minute** à être représentée par l'instance en cours de construction. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Le calendrier utilisé pour interpréter l'**année**, le **mois** et le **jour** spécifiés. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois, un jour, une heure, une minute, une seconde et une milliseconde particulières.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |
| hour | int | L'heure du **jour** à représenter par l'instance en cours de construction. |
| minute | int | La minute de l'**heure** à représenter par l'instance en cours de construction. |
| second | int | La seconde de la **minute** à être représentée par l'instance en cours de construction. |
| millisecond | int | La milliseconde de la **seconde** à représenter par l'instance en cours de construction. |
| kind | [DateTimeKind](../../datetimekind/) | La valeur qui indique si les paramètres de date et d'heure fournis spécifient une heure locale, une heure UTC ou aucune des deux. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par une année, un mois, un jour, une heure, une minute, une seconde et une milliseconde particulières dans le calendrier spécifié.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| year | int | L'année à représenter par l'instance en cours de construction. |
| month | int | Le mois de l'**année** à représenter par l'instance en cours de construction. |
| day | int | Le jour du **mois** à représenter par l'instance en cours de construction. |
| hour | int | L'heure du **jour** à représenter par l'instance en cours de construction. |
| minute | int | La minute de l'**heure** à représenter par l'instance en cours de construction. |
| second | int | La seconde de la **minute** à être représentée par l'instance en cours de construction. |
| millisecond | int | La milliseconde de la **seconde** à représenter par l'instance en cours de construction. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | La valeur qui indique si les paramètres de date et d'heure fournis spécifient une heure locale, une heure UTC ou aucune des deux. |
| calendar | [DateTimeKind](../../datetimekind/) | Le calendrier utilisé pour interpréter l'**année**, le **mois** et le **jour** spécifiés. |

## DateTime::DateTime(int64_t, DateTimeKind) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par un nombre de ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | Le nombre d'intervalles de 100 ns écoulés depuis le 1er janvier 0001 00:00:00.000 du calendrier géorgien. |
| kind | [DateTimeKind](../../datetimekind/) | La valeur qui indique si le paramètre **ticks** spécifie une heure locale, une heure UTC ou aucune des deux. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) constructeur

Construit une instance qui représente une valeur de date et d'heure spécifiée par un nombre de ticks. POUR USAGE INTERNE.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | Le nombre d'intervalles de 100 ns écoulés depuis le 1er janvier 0001 00:00:00.000 du calendrier géorgien. |
| kind | [DateTimeKind](../../datetimekind/) | La valeur qui indique si le paramètre **ticks** spécifie une heure locale, une heure UTC ou aucune des deux. |
| is_ambiguous_local_dst | **bool** | Vrai si la date et l'heure spécifiées sont ambiguës et peuvent être associées à de nombreux temps UTC. |

## DateTime::DateTime(const DateTime\&) constructeur

Construit une copie d'une instance.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Une instance de la classe [DateTime](../) dont copier la valeur de date et d'heure représentée. |

## Voir aussi

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)