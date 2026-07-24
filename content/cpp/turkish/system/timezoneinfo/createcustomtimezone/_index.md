---
title: CreateCustomTimeZone()
second_title: Aspose.Slides için C++ API Referansı
description: Özel bir saat dilimi oluşturur.
type: docs
weight: 105
url: /tr/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) metodu


Özel bir saat dilimi oluşturur.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | const [String](../../string/)\& | Saat dilimi tanımlayıcısı. |
| base_utc_offset | [TimeSpan](../../timespan/) | Mevcut saat diliminin standart zamanı ile UTC zamanı arasındaki zaman aralığı. |
| display_name | const [String](../../string/)\& | Görünen ad. |
| standard_display_name | const [String](../../string/)\& | Standart zaman adı. |
| daylight_display_name | const [String](../../string/)\& | Yaz saati uygulaması adı. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) ayarlama kurallarının. |
| disable_daylight_saving_time | **bool** | True, adjustment_rules içinde bulunan herhangi bir yaz saati uygulaması bilgisini göz ardı eder. |

### Dönüş Değeri

Yeni saat dilimi.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) metodu


Özel bir saat dilimi oluşturur.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | const [String](../../string/)\& | Saat dilimi tanımlayıcısı. |
| base_utc_offset | [TimeSpan](../../timespan/) | Mevcut saat diliminin standart zamanı ile UTC zamanı arasındaki zaman aralığı. |
| display_name | const [String](../../string/)\& | Görünen ad. |
| standard_display_name | const [String](../../string/)\& | Standart zaman adı. |
| daylight_display_name | const [String](../../string/)\& | Yaz saati uygulaması adı. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) ayarlama kurallarının. |

### Dönüş Değeri

Yeni saat dilimi.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) metodu


Özel bir saat dilimi oluşturur.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | const [String](../../string/)\& | Saat dilimi tanımlayıcısı. |
| base_utc_offset | [TimeSpan](../../timespan/) | Mevcut saat diliminin standart zamanı ile UTC zamanı arasındaki zaman aralığı. |
| display_name | const [String](../../string/)\& | Görünen ad. |
| standard_display_name | const [String](../../string/)\& | Standart zaman adı. |

### Dönüş Değeri

Yeni saat dilimi.

## İlgili

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)