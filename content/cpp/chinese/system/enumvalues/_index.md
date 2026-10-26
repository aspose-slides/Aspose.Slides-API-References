---
title: EnumValues
second_title: Aspose.Slides for C++ API 参考
description: 提供关于枚举类型 E 的枚举常量的元信息。
type: docs
weight: 794
url: /zh/system/enumvalues/
---
## EnumValues 类

提供枚举类型 **E** 的枚举常量的元信息。

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| E | 枚举的类型 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [EnumValues](./enumvalues/)() | 构造实例。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | 返回包含枚举 **E** 所有名称的数组。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | 检索指定枚举中常量名称的数组。 |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | 返回指定枚举的基础类型。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 返回指定枚举的基础类型。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | 返回具有指定名称的枚举常量的装箱值。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | 返回具有指定值的枚举常量的装箱值。 |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | 返回包含枚举 **E** 所有值的数组。 |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | 返回包含指定枚举类型所有值的数组。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 返回一个对象，表示具有指定名称的指定枚举类型的枚举常量值。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 将指定的 64 位无符号整数值转换为枚举成员。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 将具有整数值的指定对象转换为枚举成员。 |
| virtual  [~EnumValues](./~enumvalues/)() | 析构函数。 |

## 另请参见

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)