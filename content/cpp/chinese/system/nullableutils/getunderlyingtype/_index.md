---
title: GetUnderlyingType()
second_title: Aspose.Slides for C++ API 参考
description: 返回指定可空类型的底层类型参数。
type: docs
weight: 1
url: /zh/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) 方法

返回指定可空类型的底层类型参数。

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | 描述闭合泛型可空类型的 System.Type 对象。 |

### 返回值

如果 nullableType 参数是闭合泛型可空类型，则返回 nullableType 参数的类型参数；否则返回 null

## 另见

* 类 [TypeInfo](../../typeinfo/)
* 类 [NullableUtils](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)