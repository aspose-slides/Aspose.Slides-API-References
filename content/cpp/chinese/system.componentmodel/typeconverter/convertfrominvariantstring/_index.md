---
title: ConvertFromInvariantString()
second_title: Aspose.Slides C++ API 参考
description: 将不变字符串转换为对象。
type: docs
weight: 27
url: /zh/system.componentmodel/typeconverter/convertfrominvariantstring/
---
## TypeConverter::ConvertFromInvariantString(const System::String\&) method

将不变字符串转换为对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::String &text)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 要转换的值。 |

### 返回值

转换后的对象。

## TypeConverter::ConvertFromInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) method

将不变字符串转换为对象。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| text | const [System::String](../../../system/string/)\& | 要转换的值。 |

### 返回值

转换后的对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [TypeConverter](../)
* 类 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 命名空间 [System::ComponentModel](../../)
* 库 [Aspose.Slides](../../../)