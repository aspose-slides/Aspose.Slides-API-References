---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 参考
description: 将对象转换为特定类型。
type: docs
weight: 27
url: /zh/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo&) 方法

将对象转换为特定类型。

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 转换上下文信息。 |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 在转换对象时使用的文化。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) 进行转换。 |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | 要转换到的类型。 |

### 返回值

已转换的对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [ImageFormatConverter](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)