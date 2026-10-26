---
title: Convert()
second_title: Aspose.Slides for C++ API 参考
description: RTTI 信息。
type: docs
weight: 1
url: /zh/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) 方法

RTTI 信息。

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要转换的对象。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要将 value 转换为的[System::TypeInfo](../../../system/typeinfo/)。 |

### 返回值

转换后的值。

## 备注

将值转换为给定的[System::TypeInfo](../../../system/typeinfo/)。

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) 方法

将值转换为给定的[System::TypeCode](../../../system/typecode/)。

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要转换的对象。 |
| typeCode | [TypeCode](../../../system/typecode/) | 要将 value 转换为的[System::TypeCode](../../../system/typecode/)。 |

### 返回值

转换后的值。

## 另见

* 枚举 [TypeCode](../../../system/typecode/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [IFormatterConverter](../)
* 命名空间 [System::Runtime::Serialization](../../)
* 库 [Aspose.Slides](../../../)