---
title: Subtract()
second_title: Aspose.Slides C++ API 參考文件
description: 傳回一個新的 DateTime 類別實例，該實例表示從當前物件所表示的日期時間值中減去指定時間間隔後的結果日期時間值。
type: docs
weight: 326
url: /zh-hant/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const 方法

返回一個新的 [DateTime](../) 類別實例，該實例表示從當前物件所表示的日期時間值中減去指定時間間隔後的結果日期時間值。

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | 要減去的時間間隔 |

### 回傳值

一個新的 [DateTime](../) 類別實例，該實例表示從當前物件所表示的日期時間值中減去 **duration** 後的結果日期時間值。

## DateTime::Subtract(DateTime) const 方法

返回一個 [TimeSpan](../../timespan/) 類別實例，該實例表示當前物件與指定物件所表示的日期時間值之間的時間間隔。

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [DateTime](../) | 標示要計算之間隔之端點的 [DateTime](../) 類別實例 |

### 回傳值

一個 [TimeSpan](../../timespan/) 類別實例，表示當前物件與 **value** 所表示的日期時間值之間的時間間隔。

## 另請參閱

* 類別 [DateTime](../)
* 類別 [TimeSpan](../../timespan/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)