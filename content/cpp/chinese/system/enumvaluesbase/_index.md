---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API 参考
description: 用于表示枚举类型元信息的类的基类。
type: docs
weight: 807
url: /zh/system/enumvaluesbase/
---
## EnumValuesBase 类

一个用于表示枚举类型元信息的类的基类。

```cpp
class EnumValuesBase
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | 检索指定枚举中常量名称的数组。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 返回指定枚举的基础类型。 |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | 返回包含指定枚举类型所有值的数组。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 返回一个对象，表示具有指定名称的指定枚举类型的枚举常量值。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 将指定的 64 位无符号整数值转换为枚举成员。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 将具有整数值的指定对象转换为枚举成员。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)