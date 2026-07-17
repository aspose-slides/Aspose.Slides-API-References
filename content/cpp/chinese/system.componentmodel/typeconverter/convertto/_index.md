---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 参考
description: 将对象转换为特定类型。
type: docs
weight: 53
url: /zh/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 方法


将对象转换为特定类型。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要转换的对象。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要转换成的类型。 |

### 返回值

已转换的对象。

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 方法


将对象转换为特定类型。

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 转换对象时使用的区域性。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要转换的对象。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要转换成的类型。 |

### 返回值

已转换的对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [TypeConverter](../)
* 类 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System::ComponentModel](../../)
* 库 [Aspose.Slides](../../../)