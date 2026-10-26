---
title: GetWeekOfYear()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された時点の年の週番号を取得します。
type: docs
weight: 352
url: /ja/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const メソッド

指定された時点の年の週番号を取得します。

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | データを抽出する日時。 |
| rule | [CalendarWeekRule](../../calendarweekrule/) | 年の最初の週を決定する方法を決定します。 |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | 週の最初の日を決定します。 |

### 戻り値

指定された時点の年週番号。

## 参照

* 列挙型 [CalendarWeekRule](../../calendarweekrule/)
* 列挙型 [DayOfWeek](../../../system/dayofweek/)
* クラス [DateTime](../../../system/datetime/)
* クラス [Calendar](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)