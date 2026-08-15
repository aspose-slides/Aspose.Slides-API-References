---
title: operator-()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回一個新的 DateTime 類別實例，該實例表示從目前物件所代表的值減去指定時間跨度後的日期和時間值。
type: docs
weight: 651
url: /zh-hant/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const 方法


傳回 [DateTime](../) 類別的新實例，該實例表示從目前物件所代表的值減去指定時間跨度後的日期和時間值。

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 要減去的時間間隔 |

### 返回值

傳回 [DateTime](../) 類別的新實例，該實例表示從目前物件所代表的值減去 **value** 後的日期和時間值。

## DateTime::operator-(DateTime) const 方法


傳回 [TimeSpan](../../timespan/) 類別的實例，該實例表示目前物件與指定物件所代表的日期和時間值之間的時間間隔。

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [DateTime](../) | 一個 [DateTime](../) 類別的實例，標示要計算的間隔之其中一端 |

### 返回值

一個 [TimeSpan](../../timespan/) 類別的實例，表示目前物件與 **value** 所代表的日期和時間值之間的時間間隔。

## 另見

* 類別 [DateTime](../)
* 類別 [TimeSpan](../../timespan/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)