---
title: DateTimeOffset()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトコンストラクタ。
type: docs
weight: 1
url: /ja/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() コンストラクタ

デフォルトコンストラクタ。

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) コンストラクタ

コンストラクタ。

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日付と時刻。 |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) コンストラクタ

コンストラクタ。

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ticks | **int64_t** | ティックの数。 |
| offset | [TimeSpan](../../timespan/) | UTC からの時間オフセット。 |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) コンストラクタ

コンストラクタ。

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日付と時刻。 |
| offset | [TimeSpan](../../timespan/) | UTC からの時間オフセット。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) コンストラクタ

コンストラクタ。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| year | int | 年 (1 から 9999)。 |
| month | int | 月 (1 から 12)。 |
| day | int | 日 (1 からその月の日数)。 |
| hour | int | 時 (0 から 23)。 |
| minute | int | 分 (0 から 59)。 |
| second | int | 秒 (0 から 59)。 |
| offset | [TimeSpan](../../timespan/) | UTC からの時間オフセット。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) コンストラクタ

コンストラクタ。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| year | int | 年 (1 から 9999)。 |
| month | int | 月 (1 から 12)。 |
| day | int | 日 (1 からその月の日数)。 |
| hour | int | 時 (0 から 23)。 |
| minute | int | 分 (0 から 59)。 |
| second | int | 秒 (0 から 59)。 |
| millisecond | int | ミリ秒 (0 から 999)。 |
| offset | [TimeSpan](../../timespan/) | UTC からの時間オフセット。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) コンストラクタ

コンストラクタ。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| year | int | 年。 |
| month | int | 月 (1 から 12)。 |
| day | int | 日 (1 からその月の日数)。 |
| hour | int | 時 (0 から 23)。 |
| minute | int | 分 (0 から 59)。 |
| second | int | 秒 (0 から 59)。 |
| millisecond | int | ミリ秒 (0 から 999)。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 年、月、日を解釈するために使用されるカレンダー。 |
| offset | [TimeSpan](../../timespan/) | UTC からの時間オフセット。 |

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [DateTimeOffset](../)
* クラス [DateTime](../../datetime/)
* クラス [TimeSpan](../../timespan/)
* クラス [Calendar](../../../system.globalization/calendar/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)