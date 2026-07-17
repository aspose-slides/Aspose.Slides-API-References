---
title: ConvertFromString()
second_title: Aspose.Slides for C++ API 参考
description: 将字符串转换为对象。
type: docs
weight: 40
url: /zh/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) method

将字符串转换为对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 要转换的值。 |

### 返回值

已转换的对象。

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) method

将字符串转换为对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| text | const [System::String](../../../system/string/)\& | 要转换的值。 |

### 返回值

已转换的对象。

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method

将字符串转换为对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 转换对象时使用的文化。 |
| text | const [System::String](../../../system/string/)\& | 要转换的值。 |

### 返回值

已转换的对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [TypeConverter](../)
* 类 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System::ComponentModel](../../)
* 库 [Aspose.Slides](../../../)