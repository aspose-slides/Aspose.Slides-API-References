---
title: CreateCustomTimeZone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un fuso orario personalizzato.
type: docs
weight: 105
url: /it/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) metodo

Crea un fuso orario personalizzato.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificatore del fuso orario. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervallo di tempo tra l'ora standard del fuso orario corrente e l'ora UTC. |
| display_name | const [String](../../string/)\& | Nome visualizzato. |
| standard_display_name | const [String](../../string/)\& | Nome dell'ora standard. |
| daylight_display_name | const [String](../../string/)\& | Nome dell'ora legale. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) delle regole di adeguamento. |
| disable_daylight_saving_time | **bool** | True per scartare qualsiasi informazione sull'ora legale presente in adjustment_rules. |

### Valore di ritorno

Nuovo fuso orario.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) metodo

Crea un fuso orario personalizzato.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificatore del fuso orario. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervallo di tempo tra l'ora standard del fuso orario corrente e l'ora UTC. |
| display_name | const [String](../../string/)\& | Nome visualizzato. |
| standard_display_name | const [String](../../string/)\& | Nome dell'ora standard. |
| daylight_display_name | const [String](../../string/)\& | Nome dell'ora legale. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) delle regole di adeguamento. |

### Valore di ritorno

Nuovo fuso orario.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) metodo

Crea un fuso orario personalizzato.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificatore del fuso orario. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervallo di tempo tra l'ora standard del fuso orario corrente e l'ora UTC. |
| display_name | const [String](../../string/)\& | Nome visualizzato. |
| standard_display_name | const [String](../../string/)\& | Nome dell'ora standard. |

### Valore di ritorno

Nuovo fuso orario.

## Vedi anche

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)