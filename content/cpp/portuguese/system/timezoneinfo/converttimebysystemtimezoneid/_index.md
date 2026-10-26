---
title: ConvertTimeBySystemTimeZoneId()
second_title: Referência da API Aspose.Slides para C++
description: Converte o tempo para o horário em um fuso horário especificado.
type: docs
weight: 53
url: /pt/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method


[Convert](../../convert/) tempo para o horário em um fuso horário especificado.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora a converter. |
| destination_time_zone_id | const [String](../../string/)\& | Identificador do fuso horário de destino. |

### Valor de retorno

Data e hora convertidas.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method


[Convert](../../convert/) tempo para o horário em um fuso horário especificado.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data e hora a converter. |
| destination_time_zone_id | const [String](../../string/)\& | Identificador do fuso horário de destino. |

### Valor de retorno

Data e hora convertidas.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method


[Convert](../../convert/) tempo para o horário em um fuso horário especificado.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora a converter. |
| source_time_zone_id | const [String](../../string/)\& | Identificador do fuso horário de origem. |
| destination_time_zone_id | const [String](../../string/)\& | Identificador do fuso horário de destino. |

### Valor de retorno

Data e hora convertidas.

## Ver também

* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)