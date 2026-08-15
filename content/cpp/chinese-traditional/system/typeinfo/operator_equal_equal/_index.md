---
title: operator==()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷目前的 TypeInfo 物件與指定的物件是否相等。
type: docs
weight: 443
url: /zh-hant/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const method


判斷目前的與指定的 [TypeInfo](../) 物件是否相等。

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```


### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 要比較的 [TypeInfo](../) 物件 |

### Return Value

如果物件的雜湊相等則為 true，否則為 false

## TypeInfo::operator==(std::nullptr_t) const method


判斷目前的 [TypeInfo](../) 物件是否為 null-object，也就是說不代表任何型別。

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```


### Return Value

如果目前的 [TypeInfo](../) 物件為 null-object，則為 true，否則為 false

## See Also

* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)