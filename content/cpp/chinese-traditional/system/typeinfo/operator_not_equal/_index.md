---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考
description: 判斷目前的物件與指定的 TypeInfo 物件是否不相等。
type: docs
weight: 456
url: /zh-hant/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const 方法

判斷目前的物件與指定的 [TypeInfo](../) 物件是否不相等。

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 要比較的 [TypeInfo](../) 物件 |

### 返回值

如果物件的雜湊值不相等則返回 true，否則返回 false

## TypeInfo::operator!=(std::nullptr_t) const 方法

判斷目前的 [TypeInfo](../) 物件是否不是空物件，即它表示某種型別。

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### 返回值

如果目前的 [TypeInfo](../) 物件不是空物件則返回 true，否則返回 false

## 另見

* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)