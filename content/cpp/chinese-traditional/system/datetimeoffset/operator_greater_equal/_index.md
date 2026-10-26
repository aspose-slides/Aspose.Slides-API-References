---
title: operator>=()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷目前物件所表示的日期與時間值是否晚於或等於指定的 DateTimeOffset 物件所表示的值。
type: docs
weight: 599
url: /zh-hant/system/datetimeoffset/operator_greater_equal/
---
## DateTimeOffset::operator>=(const DateTimeOffset\&) const 方法

判斷目前物件所表示的日期與時間值是否晚於或等於指定的 [DateTimeOffset](../) 物件所表示的值。

```cpp
bool System::DateTimeOffset::operator>=(const DateTimeOffset &other) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 用於與目前物件比較的 [DateTimeOffset](../) 物件 |

### 回傳值

如果目前物件所表示的日期與時間值晚於或等於 **other** 所表示的值，則為 true，否則為 false

## DateTimeOffset::operator>=(std::nullptr_t) const 方法

```cpp
constexpr bool System::DateTimeOffset::operator>=(std::nullptr_t) const
```

## 另見

* 類別 [DateTimeOffset](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)