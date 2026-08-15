---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 參考
description: 將物件轉換為特定類型。
type: docs
weight: 27
url: /zh-hant/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) 方法


將物件轉換為特定類型。

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 在轉換物件時使用的文化。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要轉換的物件。 |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | 要轉換成的類型。 |

### 傳回值

已轉換的物件。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [ImageFormatConverter](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)