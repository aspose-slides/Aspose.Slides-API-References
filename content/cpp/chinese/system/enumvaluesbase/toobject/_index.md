---
title: ToObject()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的 64 位无符号整数值转换为枚举成员。
type: docs
weight: 40
url: /zh/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) 方法


将指定的 64 位无符号整数值转换为枚举成员。

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 要返回的枚举类型。 |
| value | **uint64_t** | 要转换为枚举成员的值。 |

### 返回值

一个设置为该值的枚举实例。

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) 方法


将具有整数值的指定对象转换为枚举成员。

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 要返回的枚举类型。 |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要转换为枚举成员的值。 |

### 返回值

一个其值为该值的枚举对象。

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Object](../../object/)
* 类 [TypeInfo](../../typeinfo/)
* 类 [EnumValuesBase](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)