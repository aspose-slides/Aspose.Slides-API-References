---
title: DateTimeOffset()
second_title: Referência da API Aspose.Slides para C++
description: Construtor padrão.
type: docs
weight: 1
url: /pt/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() construtor

Construtor padrão.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) construtor

Construtor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) construtor

Construtor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ticks | **int64_t** | Número de ticks. |
| offset | [TimeSpan](../../timespan/) | Deslocamento de tempo em relação ao UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) construtor

Construtor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora. |
| offset | [TimeSpan](../../timespan/) | Deslocamento de tempo em relação ao UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) construtor

Construtor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | Ano (de 1 a 9999). |
| month | int | Mês (de 1 a 12). |
| day | int | Dia (de 1 ao número de dias no mês). |
| hour | int | Hora (de 0 a 23). |
| minute | int | Minuto (de 0 a 59). |
| second | int | Segundo (de 0 a 59). |
| offset | [TimeSpan](../../timespan/) | Deslocamento de tempo em relação ao UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) construtor

Construtor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | Ano (de 1 a 9999). |
| month | int | Mês (de 1 a 12). |
| day | int | Dia (de 1 ao número de dias no mês). |
| hour | int | Hora (de 0 a 23). |
| minute | int | Minuto (de 0 a 59). |
| second | int | Segundo (de 0 a 59). |
| millisecond | int | Milissegundo (de 0 a 999). |
| offset | [TimeSpan](../../timespan/) | Deslocamento de tempo em relação ao UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) construtor

Construtor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | Ano. |
| month | int | Mês (de 1 a 12). |
| day | int | Dia (de 1 ao número de dias no mês). |
| hour | int | Hora (de 0 a 23). |
| minute | int | Minuto (de 0 a 59). |
| second | int | Segundo (de 0 a 59). |
| millisecond | int | Milissegundo (de 0 a 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Calendário usado para interpretar ano, mês e dia. |
| offset | [TimeSpan](../../timespan/) | Deslocamento de tempo em relação ao UTC. |

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTimeOffset](../)
* Classe [DateTime](../../datetime/)
* Classe [TimeSpan](../../timespan/)
* Classe [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)