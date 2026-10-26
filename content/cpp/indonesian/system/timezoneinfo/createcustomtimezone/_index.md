---
title: CreateCustomTimeZone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat zona waktu khusus.
type: docs
weight: 105
url: /id/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) metode

Membuat zona waktu khusus.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifikasi zona waktu. |
| base_utc_offset | [TimeSpan](../../timespan/) | Interval waktu antara waktu standar zona waktu saat ini dan waktu UTC. |
| display_name | const [String](../../string/)\& | Nama tampilan. |
| standard_display_name | const [String](../../string/)\& | Nama waktu standar. |
| daylight_display_name | const [String](../../string/)\& | Nama waktu daylight saving time. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) of adjustment rules. |
| disable_daylight_saving_time | **bool** | True untuk mengabaikan semua informasi daylight saving time yang ada di adjustment_rules. |

### Nilai Kembali

Zona waktu baru.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) metode

Membuat zona waktu khusus.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifikasi zona waktu. |
| base_utc_offset | [TimeSpan](../../timespan/) | Interval waktu antara waktu standar zona waktu saat ini dan waktu UTC. |
| display_name | const [String](../../string/)\& | Nama tampilan. |
| standard_display_name | const [String](../../string/)\& | Nama waktu standar. |
| daylight_display_name | const [String](../../string/)\& | Nama waktu daylight saving time. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) of adjustment rules. |

### Nilai Kembali

Zona waktu baru.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) metode

Membuat zona waktu khusus.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifikasi zona waktu. |
| base_utc_offset | [TimeSpan](../../timespan/) | Interval waktu antara waktu standar zona waktu saat ini dan waktu UTC. |
| display_name | const [String](../../string/)\& | Nama tampilan. |
| standard_display_name | const [String](../../string/)\& | Nama waktu standar. |

### Nilai Kembali

Zona waktu baru.

## Lihat Juga

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Kelas [String](../../string/)
* Kelas [TimeSpan](../../timespan/)
* Kelas [TimeZoneInfo](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)