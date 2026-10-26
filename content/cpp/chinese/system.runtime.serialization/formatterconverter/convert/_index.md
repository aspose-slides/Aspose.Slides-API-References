---
title: Convert()
second_title: Aspose.Slides for C++ API 参考
description: "将值转换为给定的 System::TypeInfo。"
type: docs
weight: 1
url: /zh/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

将值转换为给定的 [System::TypeInfo](../../../system/typeinfo/)。

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要转换的对象。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要将值转换为的 [System::TypeInfo](../../../system/typeinfo/)。 |

### 返回值

转换后的值。

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

将值转换为给定的 [System::TypeCode](../../../system/typecode/)。

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要转换的对象。 |
| typeCode | [TypeCode](../../../system/typecode/) | 要将值转换为的 [System::TypeCode](../../../system/typecode/)。 |

### 返回值

转换后的值。

## 另请参阅

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [FormatterConverter](../)
* 命名空间 [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)