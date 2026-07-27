---
title: ConvertTime()
second_title: Aspose.Slides for C++ Referência da API
description: Converte o horário de um fuso horário para outro.
type: docs
weight: 40
url: /pt/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) método

[Convert](../../convert/) tempo de um fuso horário para outro.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora a converter. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuso horário de origem. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuso horário de destino. |

### Valor de Retorno

Data e hora convertidas.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) método

[Convert](../../convert/) tempo para o horário em um fuso horário especificado.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data e hora a converter. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuso horário de destino. |

### Valor de Retorno

Data e hora convertidas.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) método

[Convert](../../convert/) tempo para o horário em um fuso horário especificado.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora a converter. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuso horário de destino. |

### Valor de Retorno

Data e hora convertidas.

## Veja Também

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Classe [DateTime](../../datetime/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)