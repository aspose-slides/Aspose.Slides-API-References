---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API 参考
description: 转换对象。
type: docs
weight: 14
url: /zh/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) 方法


转换对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要转换的。 |

### 返回值

转换后的对象。

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) 方法


转换对象。

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 在转换对象时使用的文化。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要转换的。 |

### 返回值

转换后的对象。

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) 方法


将字符串转换为对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 在转换对象时使用的文化。 |
| value | const [System::String](../../../system/string/)\& | 要转换的值。 |

### 返回值

转换后的对象。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeConverter](../)
* 类 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [String](../../../system/string/)
* 命名空间 [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)