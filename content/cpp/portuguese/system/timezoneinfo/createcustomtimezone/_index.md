---
title: CreateCustomTimeZone()
second_title: Referência da API Aspose.Slides for C++
description: Cria um fuso horário personalizado.
type: docs
weight: 105
url: /pt/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

Cria um fuso horário personalizado.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificador do fuso horário. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalo de tempo entre o horário padrão do fuso horário atual e o horário UTC. |
| display_name | const [String](../../string/)\& | Nome de exibição. |
| standard_display_name | const [String](../../string/)\& | Nome do horário padrão. |
| daylight_display_name | const [String](../../string/)\& | Nome do horário de verão. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) de regras de ajuste. |
| disable_daylight_saving_time | **bool** | True para descartar qualquer informação de horário de verão presente em adjustment_rules. |

### Valor de Retorno

Novo fuso horário.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

Cria um fuso horário personalizado.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificador do fuso horário. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalo de tempo entre o horário padrão do fuso horário atual e o horário UTC. |
| display_name | const [String](../../string/)\& | Nome de exibição. |
| standard_display_name | const [String](../../string/)\& | Nome do horário padrão. |
| daylight_display_name | const [String](../../string/)\& | Nome do horário de verão. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) de regras de ajuste. |

### Valor de Retorno

Novo fuso horário.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

Cria um fuso horário personalizado.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identificador do fuso horário. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalo de tempo entre o horário padrão do fuso horário atual e o horário UTC. |
| display_name | const [String](../../string/)\& | Nome de exibição. |
| standard_display_name | const [String](../../string/)\& | Nome do horário padrão. |

### Valor de Retorno

Novo fuso horário.

## Veja Também

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../../timespan/)
* Classe [TimeZoneInfo](../)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)