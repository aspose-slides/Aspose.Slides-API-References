---
title: operator<()
second_title: Aspose.Slides for C++ API 參考手冊
description: 判斷目前物件所代表的日期時間值是否早於指定的 DateTime 物件所代表的值。
type: docs
weight: 586
url: /zh-hant/system/datetime/operator_less/
---
## DateTime::operator<(DateTime) const 方法

判斷目前的物件所代表的日期與時間值是否早於由指定的 [DateTime](../) 物件所代表的值。

```cpp
constexpr bool System::DateTime::operator<(DateTime other) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | [DateTime](../) | 用於與目前物件比較的 [DateTime](../) 物件 |

### 返回值

True if the date and time value represented by the current object is earlier than the value represented by **other**, otherwise - false

## DateTime::operator<(std::nullptr_t) const 方法

```cpp
constexpr bool System::DateTime::operator<(std::nullptr_t) const
```

## 參見

* 類別 [DateTime](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)