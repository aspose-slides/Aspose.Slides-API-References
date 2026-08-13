---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API 참조
description: 사용자 정의 시간대를 생성합니다.
type: docs
weight: 105
url: /ko/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

사용자 정의 시간대를 생성합니다.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 시간대 식별자. |
| base_utc_offset | [TimeSpan](../../timespan/) | 현재 시간대의 표준시와 UTC 시간 사이의 시간 간격. |
| display_name | const [String](../../string/)\& | 표시 이름. |
| standard_display_name | const [String](../../string/)\& | 표준 시간 이름. |
| daylight_display_name | const [String](../../string/)\& | 일광 절약 시간 이름. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) 조정 규칙. |
| disable_daylight_saving_time | **bool** | 조정 규칙에 포함된 일광 절약 시간 정보를 무시하려면 true. |

### 반환값

새 시간대.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

사용자 정의 시간대를 생성합니다.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 시간대 식별자. |
| base_utc_offset | [TimeSpan](../../timespan/) | 현재 시간대의 표준시와 UTC 시간 사이의 시간 간격. |
| display_name | const [String](../../string/)\& | 표시 이름. |
| standard_display_name | const [String](../../string/)\& | 표준 시간 이름. |
| daylight_display_name | const [String](../../string/)\& | 일광 절약 시간 이름. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) 조정 규칙. |

### 반환값

새 시간대.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

사용자 정의 시간대를 생성합니다.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 시간대 식별자. |
| base_utc_offset | [TimeSpan](../../timespan/) | 현재 시간대의 표준시와 UTC 시간 사이의 시간 간격. |
| display_name | const [String](../../string/)\& | 표시 이름. |
| standard_display_name | const [String](../../string/)\& | 표준 시간 이름. |

### 반환값

새 시간대.

## 참조

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* 클래스 [String](../../string/)
* 클래스 [TimeSpan](../../timespan/)
* 클래스 [TimeZoneInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)