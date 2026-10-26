---
title: Equals()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷目前物件所代表的值是否等於指定的 Nullable 物件所代表的值。
type: docs
weight: 131
url: /zh-hant/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const 方法

判斷目前物件所代表的值是否等於指定的 [Nullable](../) 物件所代表的值。

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T1 | 用於比較之 [Nullable](../) 物件的底層型別 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | 指向要比較之 [Nullable](../) 物件的常量參照 |

### 傳回值

若目前物件所代表的值與指定的 [Nullable](../) 物件所代表的值相等，則返回 true，否則返回 false

## 另請參閱

* 類別 [Nullable](../)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)