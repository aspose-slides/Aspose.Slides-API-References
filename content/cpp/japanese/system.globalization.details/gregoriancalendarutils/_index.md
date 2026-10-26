---
title: GregorianCalendarUtils
second_title: C++ 用 Aspose.Slides API リファレンス
description: グレゴリオ暦ユーティリティ関数。
type: docs
weight: 1
url: /ja/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils クラス

グレゴリオ暦ユーティリティ関数。

```cpp
class GregorianCalendarUtils
```

## メソッド

| Method | 説明 |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) を ICU UDate に。 |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate を [DateTime](../../system/datetime/) に。 |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | グレゴリオ暦の ICU カレンダーを作成します。 |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | スレッドローカルのグレゴリオ暦 ICU カレンダーを取得します。 |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | 特定の月の日数を取得します。 |
| static int [GetDaysInYear](./getdaysinyear/)(int) | 特定の年の日数を取得します。 |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | 日が閏日かどうかを確認します。 |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 年が閏年かどうかを確認します。 |

## フィールド

| Field | 説明 |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | サポートされている最大のグレゴリオ暦年。 |
| static constexpr [MinYear](./minyear/) | サポートされている最小のグレゴリオ暦年。 |

## 参照

* 名前空間 [System::Globalization::Details](../)
* ライブラリ [Aspose.Slides](../../)