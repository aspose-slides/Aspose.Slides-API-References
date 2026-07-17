---
title: Parse()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个对象，该对象表示具有指定名称的指定枚举类型的枚举常量值。
type: docs
weight: 27
url: /zh/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) 方法


返回一个对象，该对象表示具有指定名称的指定枚举类型的枚举常量值。

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 表示要返回的枚举值类型的 [TypeInfo](../../typeinfo/) 对象 |
| str | const [String](../../string/)\& | 枚举常量的名称 |
| ignoreCase | **bool** | 指定在解释枚举常量名称时是否应忽略大小写 |

### 返回值

一个对象，表示名称在 **str** 中指定的枚举常量的值。

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Object](../../object/)
* 类 [TypeInfo](../../typeinfo/)
* 类 [String](../../string/)
* 类 [EnumValuesBase](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)