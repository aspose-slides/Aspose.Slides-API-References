---
title: TimeSpan()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個代表零時間間隔的 TimeSpan 物件。
type: docs
weight: 1
url: /zh-hant/system/timespan/timespan/
---
## TimeSpan::TimeSpan() 建構子

建立一個代表零時間間隔的 [TimeSpan](../) 物件。

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) 建構子

建立一個代表指定時間間隔的 [TimeSpan](../) 類別實例。

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ticks | **int64_t** | 以 100 納秒間隔的個數表示，要由所建構之實例所代表的時間間隔。 |

## TimeSpan::TimeSpan(int, int, int) 建構子

建立一個代表時間間隔的 [TimeSpan](../) 類別實例，該時間間隔等於指定的小時、分鐘和秒數之總和。

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| hours | int | 要由所建構的實例所代表的時間間隔之小時部分的數量 |
| minutes | int | 要由所建構的實例所代表的時間間隔之分鐘部分的數量 |
| seconds | int | 要由所建構的實例所代表的時間間隔之秒數部分的數量 |

## TimeSpan::TimeSpan(int, int, int, int, int) 建構子

建立一個代表時間間隔的 [TimeSpan](../) 類別實例，該時間間隔等於指定的天、時、分、秒與毫秒之總和。

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| days | int | 要由所建構的實例所代表的時間間隔之天數部分的數量 |
| hours | int | 要由所建構的實例所代表的時間間隔之小時部分的數量 |
| minutes | int | 要由所建構的實例所代表的時間間隔之分鐘部分的數量 |
| seconds | int | 要由所建構的實例所代表的時間間隔之秒數部分的數量 |
| milliseconds | int | 要由所建構的實例所代表的時間間隔之毫秒部分的數量 |

## TimeSpan::TimeSpan(const TimeSpan\&) 建構子

建立一個代表與指定的 [TimeSpan](../) 物件所表示的時間間隔相等的 [TimeSpan](../) 物件。

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## 另見

* 類別 [TimeSpan](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)