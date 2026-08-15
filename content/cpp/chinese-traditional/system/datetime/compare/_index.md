---
title: Compare()
second_title: Aspose.Slides for C++ API 參考
description: 比較由指定的 DateTime 類別實例所表示的兩個值，並返回指示這些值在時間軸上相對位置的值。
type: docs
weight: 846
url: /zh-hant/system/datetime/compare/
---
## DateTime::Compare(DateTime, DateTime) 方法


比較由指定的 [DateTime](../) 類別實例所表示的兩個值，並返回指示這些值在時間軸上相對位置的值。

```cpp
static constexpr int System::DateTime::Compare(DateTime t1, DateTime t2)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| t1 | [DateTime](../) | 第一個比較項 |
| t2 | [DateTime](../) | 第二個比較項 |

### 返回值

如果 **t1** 早於 **t2**，則返回小於 0 的值；如果 **t1** 與 **t2** 相同，則返回 0；如果 **t1** 晚於 **t2**，則返回大於 0 的值。

## 另見

* 類別 [DateTime](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)