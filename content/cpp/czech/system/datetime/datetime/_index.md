---
title: DateTime()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří instanci, která představuje nejmenší možnou hodnotu data a času, rovnající se MinValue.
type: docs
weight: 1
url: /cs/system/datetime/datetime/
---
## DateTime::DateTime() konstruktor

Vytvoří instanci, která představuje nejmenší možnou hodnotu data a času, rovnající se MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem a dnem.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem a dnem v určeném kalendáři.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendář použitý k interpretaci určených **roku**, **měsíce** a **dne**. |

## DateTime::DateTime(int, int, int, int, int, int) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem, dnem, hodinou, minutou a sekundou.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |
| hour | int | Hodina **dne**, která má být reprezentována vytvářenou instancí. |
| minute | int | Minuta **hodiny**, která má být reprezentována vytvářenou instancí. |
| second | int | Sekunda **minuty**, která má být reprezentována vytvářenou instancí. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem, dnem, hodinou, minutou a sekundou.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |
| hour | int | Hodina **dne**, která má být reprezentována vytvářenou instancí. |
| minute | int | Minuta **hodiny**, která má být reprezentována vytvářenou instancí. |
| second | int | Sekunda **minuty**, která má být reprezentována vytvářenou instancí. |
| kind | [DateTimeKind](../../datetimekind/) | Hodnota, která určuje, zda zadané parametry data a času specifikují lokální čas, čas UTC nebo žádný z nich. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem, dnem, hodinou, minutou a sekundou v určeném kalendáři.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |
| hour | int | Hodina **dne**, která má být reprezentována vytvářenou instancí. |
| minute | int | Minuta **hodiny**, která má být reprezentována vytvářenou instancí. |
| second | int | Sekunda **minuty**, která má být reprezentována vytvářenou instancí. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendář použitý k interpretaci určených **roku**, **měsíce** a **dne**. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem, dnem, hodinou, minutou, sekundou a milisekundou.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |
| hour | int | Hodina **dne**, která má být reprezentována vytvářenou instancí. |
| minute | int | Minuta **hodiny**, která má být reprezentována vytvářenou instancí. |
| second | int | Sekunda **minuty**, která má být reprezentována vytvářenou instancí. |
| millisecond | int | Milisekunda **sekundy**, která má být reprezentována vytvářenou instancí. |
| kind | [DateTimeKind](../../datetimekind/) | Hodnota, která určuje, zda zadané parametry data a času specifikují lokální čas, čas UTC nebo žádný z nich. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou konkrétním rokem, měsícem, dnem, hodinou, minutou, sekundou a milisekundou v určeném kalendáři.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok, který má být reprezentován vytvářenou instancí. |
| month | int | Měsíc v **roce**, který má být reprezentován vytvářenou instancí. |
| day | int | Den v **měsíci**, který má být reprezentován vytvářenou instancí. |
| hour | int | Hodina **dne**, která má být reprezentována vytvářenou instancí. |
| minute | int | Minuta **hodiny**, která má být reprezentována vytvářenou instancí. |
| second | int | Sekunda **minuty**, která má být reprezentována vytvářenou instancí. |
| millisecond | int | Milisekunda **sekundy**, která má být reprezentována vytvářenou instancí. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Hodnota, která určuje, zda zadané parametry data a času specifikují lokální čas, čas UTC nebo žádný z nich. |
| calendar | [DateTimeKind](../../datetimekind/) | Kalendář použitý k interpretaci určených **roku**, **měsíce** a **dne**. |

## DateTime::DateTime(int64_t, DateTimeKind) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou počtem tiků.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ticks | **int64_t** | Počet 100-ns intervalů, které uplynuly od 1. ledna 0001 00:00:00.000 v gruzínském kalendáři. |
| kind | [DateTimeKind](../../datetimekind/) | Hodnota, která určuje, zda **ticks** parametr specifikuje lokální čas, čas UTC nebo žádný z nich. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) konstruktor

Vytvoří instanci, která představuje hodnotu data a času určenou počtem tiků. PRO INTERNÍ POUŽITÍ.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ticks | **int64_t** | Počet 100-ns intervalů, které uplynuly od 1. ledna 0001 00:00:00.000 v gruzínském kalendáři. |
| kind | [DateTimeKind](../../datetimekind/) | Hodnota, která určuje, zda **ticks** parametr specifikuje lokální čas, čas UTC nebo žádný z nich. |
| is_ambiguous_local_dst | **bool** | Pravda, pokud je určené datum a čas nejednoznačný a může být přiřazen k mnoha časům UTC. |

## DateTime::DateTime(const DateTime\&) konstruktor

Kopírově-konstruuje instanci.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Instance třídy [DateTime](../) ze které se zkopíruje reprezentovaná hodnota data a času. |

## Viz také

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [DateTime](../)
* Třída [Calendar](../../../system.globalization/calendar/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)