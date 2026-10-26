---
title: DateTimeOffset()
second_title: Aspose.Slides C++ API 參考文件
description: 預設建構函式。
type: docs
weight: 1
url: /zh-hant/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() 建構函式

預設建構函式。

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) 建構函式

建構函式。

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和時間。 |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) 建構函式

建構函式。

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ticks | **int64_t** | 刻度數。 |
| offset | [TimeSpan](../../timespan/) | UTC 的時間偏移。 |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) 建構函式

建構函式。

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和時間。 |
| offset | [TimeSpan](../../timespan/) | UTC 的時間偏移。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) 建構函式

建構函式。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| year | int | 年份（1 到 9999）。 |
| month | int | 月份（1 到 12）。 |
| day | int | 天數（1 到當月天數）。 |
| hour | int | 小時（0 到 23）。 |
| minute | int | 分鐘（0 到 59）。 |
| second | int | 秒（0 到 59）。 |
| offset | [TimeSpan](../../timespan/) | UTC 的時間偏移。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) 建構函式

建構函式。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| year | int | 年份（1 到 9999）。 |
| month | int | 月份（1 到 12）。 |
| day | int | 天數（1 到當月天數）。 |
| hour | int | 小時（0 到 23）。 |
| minute | int | 分鐘（0 到 59）。 |
| second | int | 秒（0 到 59）。 |
| millisecond | int | 毫秒（0 到 999）。 |
| offset | [TimeSpan](../../timespan/) | UTC 的時間偏移。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) 建構函式

建構函式。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| year | int | 年份。 |
| month | int | 月份（1 到 12）。 |
| day | int | 天數（1 到當月天數）。 |
| hour | int | 小時（0 到 23）。 |
| minute | int | 分鐘（0 到 59）。 |
| second | int | 秒（0 到 59）。 |
| millisecond | int | 毫秒（0 到 999）。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 用於解釋年份、月份和日期的日曆。 |
| offset | [TimeSpan](../../timespan/) | UTC 的時間偏移。 |

## 另請參閱

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [DateTimeOffset](../)
* 類別 [DateTime](../../datetime/)
* 類別 [TimeSpan](../../timespan/)
* 類別 [Calendar](../../../system.globalization/calendar/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)