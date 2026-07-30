---
title: GetAmbiguousTimeOffsets()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce le date e gli orari UTC a cui una data e ora specificate possono essere mappate.
type: docs
weight: 261
url: /it/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const metodo

Restituisce le date e gli orari UTC a cui una data e ora specificate possono essere mappate.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data e ora. |

### Valore di ritorno

[Array](../../array/) di date e orari UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const metodo

Restituisce le date e gli orari UTC a cui una data e ora specificate possono essere mappate.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data e ora. |

### Valore di ritorno

[Array](../../array/) di date e orari UTC.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [TimeSpan](../../timespan/)
* Classe [DateTime](../../datetime/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)