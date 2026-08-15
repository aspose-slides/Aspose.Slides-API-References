---
title: CompareTo()
second_title: Aspose.Slides C++ API 參考文件
description: 比較目前物件與指定的 DateTime 類別實例所表示的兩個日期和時間值，並返回表示這些值在時間軸上相對位置的值。
type: docs
weight: 443
url: /zh-hant/system/datetime/compareto/
---
## DateTime::CompareTo(DateTime) const 方法

比較目前物件與指定的 [DateTime](../) 類別實例所表示的兩個日期和時間值，並返回表示這些值在時間軸上相對位置的值。

```cpp
constexpr int System::DateTime::CompareTo(DateTime value) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | 與目前物件比較的 [DateTime](../) 類別實例 |

### 返回值

如果目前物件表示的值早於 **value** 所代表的值，則返回小於 0 的值；如果兩個物件所代表的值相同，則返回 0；如果目前物件表示的值晚於 **value** 所代表的值，則返回大於 0 的值。

## 參見

* 類別 [DateTime](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)