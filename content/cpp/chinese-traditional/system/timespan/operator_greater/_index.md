---
title: operator>()
second_title: Aspose.Slides for C++ API 參考
description: 判斷目前物件所代表的時間間隔是否長於指定物件所代表的時間間隔。
type: docs
weight: 404
url: /zh-hant/system/timespan/operator_greater/
---
## TimeSpan::operator>(TimeSpan) const 方法

判斷目前物件所代表的時間間隔是否長於指定物件所代表的時間間隔。

```cpp
constexpr bool System::TimeSpan::operator>(TimeSpan value) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [TimeSpan](../) | 與當前物件比較的 [TimeSpan](../) 物件 |

### 返回值

如果當前物件所代表的時間間隔長於由 **value** 所代表的時間間隔，則為 true，否則為 false

## TimeSpan::operator>(std::nullptr_t) const 方法

```cpp
constexpr bool System::TimeSpan::operator>(std::nullptr_t) const
```

## 參見

* 類別 [TimeSpan](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)