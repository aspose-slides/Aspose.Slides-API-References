---
title: operator>()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷當前物件所表示的日期和時間值是否晚於指定的 DateTimeOffset 物件所代表的值。
type: docs
weight: 573
url: /zh-hant/system/datetimeoffset/operator_greater/
---
## DateTimeOffset::operator>(const DateTimeOffset\&) const method

判斷當前物件所表示的日期和時間值是否晚於由指定的 [DateTimeOffset](../) 物件所代表的值。

```cpp
bool System::DateTimeOffset::operator>(const DateTimeOffset &other) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 要與當前物件比較的 [DateTimeOffset](../) 物件 |

### 回傳值

如果當前物件所表示的日期和時間值晚於 **other** 所代表的值，則返回 True；否則返回 false

## DateTimeOffset::operator>(std::nullptr_t) const method

```cpp
constexpr bool System::DateTimeOffset::operator>(std::nullptr_t) const
```

## 參考

* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)