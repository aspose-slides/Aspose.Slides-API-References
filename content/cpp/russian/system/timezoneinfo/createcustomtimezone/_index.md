---
title: CreateCustomTimeZone()
second_title: Aspose.Slides для C++ справочник API
description: Создает пользовательский часовой пояс.
type: docs
weight: 105
url: /ru/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) метод


Создает пользовательский часовой пояс.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | const [String](../../string/)\& | Идентификатор часового пояса. |
| base_utc_offset | [TimeSpan](../../timespan/) | Временной интервал между стандартным временем текущего часового пояса и временем UTC. |
| display_name | const [String](../../string/)\& | Отображаемое имя. |
| standard_display_name | const [String](../../string/)\& | Название стандартного времени. |
| daylight_display_name | const [String](../../string/)\& | Название летнего времени. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) правил корректировки. |
| disable_daylight_saving_time | **bool** | True, чтобы исключить любую информацию о переходе на летнее время, присутствующую в adjustment_rules. |

### Возвращаемое значение

Новый часовой пояс.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) метод


Создает пользовательский часовой пояс.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | const [String](../../string/)\& | Идентификатор часового пояса. |
| base_utc_offset | [TimeSpan](../../timespan/) | Временной интервал между стандартным временем текущего часового пояса и временем UTC. |
| display_name | const [String](../../string/)\& | Отображаемое имя. |
| standard_display_name | const [String](../../string/)\& | Название стандартного времени. |
| daylight_display_name | const [String](../../string/)\& | Название летнего времени. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) правил корректировки. |

### Возвращаемое значение

Новый часовой пояс.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) метод


Создает пользовательский часовой пояс.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | const [String](../../string/)\& | Идентификатор часового пояса. |
| base_utc_offset | [TimeSpan](../../timespan/) | Временной интервал между стандартным временем текущего часового пояса и временем UTC. |
| display_name | const [String](../../string/)\& | Отображаемое имя. |
| standard_display_name | const [String](../../string/)\& | Название стандартного времени. |

### Возвращаемое значение

Новый часовой пояс.

## Смотрите также

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Класс [String](../../string/)
* Класс [TimeSpan](../../timespan/)
* Класс [TimeZoneInfo](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)