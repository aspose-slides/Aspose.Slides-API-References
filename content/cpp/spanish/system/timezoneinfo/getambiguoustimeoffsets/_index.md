---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides para C++ Referencia de API
description: Obtiene las fechas y horas UTC a las que se puede mapear una fecha y hora especificada.
type: docs
weight: 261
url: /es/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const método

Obtiene las fechas y horas UTC a las que se puede mapear una fecha y hora especificadas.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Fecha y hora. |

### Valor de retorno

[Array](../../array/) de fechas y horas UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const método

Obtiene las fechas y horas UTC a las que se puede mapear una fecha y hora especificadas.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Fecha y hora. |

### Valor de retorno

[Array](../../array/) de fechas y horas UTC.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [TimeSpan](../../timespan/)
* Clase [DateTime](../../datetime/)
* Clase [TimeZoneInfo](../)
* Clase [DateTimeOffset](../../datetimeoffset/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)