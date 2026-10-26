---
title: GetAmbiguousTimeOffsets()
second_title: Referência da API Aspose.Slides para C++
description: Obtém datas e horas UTC para as quais uma data e hora especificadas podem ser mapeadas.
type: docs
weight: 261
url: /pt/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const método


Obtém datas e horas UTC para as quais uma data e hora especificadas podem ser mapeadas.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e hora. |

### Valor de Retorno

[Array](../../array/) de datas e horas UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const método


Obtém datas e horas UTC para as quais uma data e hora especificadas podem ser mapeadas.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data e hora. |

### Valor de Retorno

[Array](../../array/) de datas e horas UTC.

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [TimeSpan](../../timespan/)
* Classe [DateTime](../../datetime/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)