---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 参考
description: 将对象转换为特定类型。
type: docs
weight: 14
url: /zh/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


将对象转换为特定类型。

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 在转换对象时使用的文化 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 要转换的对象。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要转换成的类型。 |

### 返回值

已转换的对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [ImageConverter](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)