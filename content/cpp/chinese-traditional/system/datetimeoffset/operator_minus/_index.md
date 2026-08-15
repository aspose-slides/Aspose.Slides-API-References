---
title: operator-()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個新的 DateTimeOffset 類別實例，表示從當前物件所代表的值減去指定時間間隔後的日期和時間值。
type: docs
weight: 521
url: /zh-hant/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const 方法


返回一個新的 [DateTimeOffset](../) 類別實例，表示從當前物件所代表的日期時間值減去指定時間間隔後的結果。

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 要減去的時間間隔 |

### 回傳值

一個新的 [DateTimeOffset](../) 類別實例，表示從當前物件所代表的日期時間值減去 **value** 後的結果。

## DateTimeOffset::operator-(const DateTimeOffset\&) const 方法


返回一個 [TimeSpan](../../timespan/) 類別實例，表示當前物件與指定物件之間的日期時間值之時間間隔。

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 標記要計算的間隔一端的 [DateTime](../../datetime/) 類別實例 |

### 回傳值

一個 [TimeSpan](../../timespan/) 類別實例，表示當前物件與 **other** 之間的日期時間值的時間間隔。

## 另見

* 類別 [DateTimeOffset](../)
* 類別 [TimeSpan](../../timespan/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)