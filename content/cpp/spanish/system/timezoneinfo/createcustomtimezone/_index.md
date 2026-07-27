---
title: CreateCustomTimeZone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una zona horaria personalizada.
type: docs
weight: 105
url: /es/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) método


Crea una zona horaria personalizada.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificador de zona horaria. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalo de tiempo entre la hora estándar de la zona horaria actual y la hora UTC. |
| display_name | const [String](../../string/)\& | Nombre para mostrar. |
| standard_display_name | const [String](../../string/)\& | Nombre de la hora estándar. |
| daylight_display_name | const [String](../../string/)\& | Nombre del horario de verano. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) de reglas de ajuste. |
| disable_daylight_saving_time | **bool** | Verdadero para descartar cualquier información de horario de verano presente en adjustment_rules. |

### Valor devuelto

Nueva zona horaria.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) método


Crea una zona horaria personalizada.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificador de zona horaria. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalo de tiempo entre la hora estándar de la zona horaria actual y la hora UTC. |
| display_name | const [String](../../string/)\& | Nombre para mostrar. |
| standard_display_name | const [String](../../string/)\& | Nombre de la hora estándar. |
| daylight_display_name | const [String](../../string/)\& | Nombre del horario de verano. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) de reglas de ajuste. |

### Valor devuelto

Nueva zona horaria.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) método


Crea una zona horaria personalizada.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificador de zona horaria. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalo de tiempo entre la hora estándar de la zona horaria actual y la hora UTC. |
| display_name | const [String](../../string/)\& | Nombre para mostrar. |
| standard_display_name | const [String](../../string/)\& | Nombre de la hora estándar. |

### Valor devuelto

Nueva zona horaria.

## Ver también

* Definición de tipo [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Definición de tipo [ArrayPtr](../../arrayptr/)
* Definición de tipo [AdjustmentRulePtr](../adjustmentruleptr/)
* Clase [String](../../string/)
* Clase [TimeSpan](../../timespan/)
* Clase [TimeZoneInfo](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)