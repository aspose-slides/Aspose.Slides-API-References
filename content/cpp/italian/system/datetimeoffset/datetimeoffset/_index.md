---
title: DateTimeOffset()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore predefinito.
type: docs
weight: 1
url: /it/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() costruttore

Costruttore predefinito.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) costruttore

Costruttore.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e ora. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) costruttore

Costruttore.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ticks | **int64_t** | Numero di tick. |
| offset | [TimeSpan](../../timespan/) | Scostamento di tempo da UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) costruttore

Costruttore.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e ora. |
| offset | [TimeSpan](../../timespan/) | Scostamento di tempo da UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) costruttore

Costruttore.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | Anno (da 1 a 9999). |
| month | int | Mese (da 1 a 12). |
| day | int | Giorno (da 1 al numero di giorni nel mese). |
| hour | int | Ora (da 0 a 23). |
| minute | int | Minuto (da 0 a 59). |
| second | int | Secondo (da 0 a 59). |
| offset | [TimeSpan](../../timespan/) | Scostamento di tempo da UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) costruttore

Costruttore.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | Anno (da 1 a 9999). |
| month | int | Mese (da 1 a 12). |
| day | int | Giorno (da 1 al numero di giorni nel mese). |
| hour | int | Ora (da 0 a 23). |
| minute | int | Minuto (da 0 a 59). |
| second | int | Secondo (da 0 a 59). |
| millisecond | int | Millisecondo (da 0 a 999). |
| offset | [TimeSpan](../../timespan/) | Scostamento di tempo da UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) costruttore

Costruttore.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | Anno. |
| month | int | Mese (da 1 a 12). |
| day | int | Giorno (da 1 al numero di giorni nel mese). |
| hour | int | Ora (da 0 a 23). |
| minute | int | Minuto (da 0 a 59). |
| second | int | Secondo (da 0 a 59). |
| millisecond | int | Millisecondo (da 0 a 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Calendario usato per interpretare anno, mese e giorno. |
| offset | [TimeSpan](../../timespan/) | Scostamento di tempo da UTC. |

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTimeOffset](../)
* Classe [DateTime](../../datetime/)
* Classe [TimeSpan](../../timespan/)
* Classe [Calendar](../../../system.globalization/calendar/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)