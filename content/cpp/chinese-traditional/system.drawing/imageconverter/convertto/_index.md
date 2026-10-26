---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 參考
description: 將物件轉換為特定類型。
type: docs
weight: 14
url: /zh-hant/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 方法

將物件轉換為特定類型。

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 轉換物件時使用的文化 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 要轉換的物件。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要轉換的類型。 |

### 返回值

已轉換的物件。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [ImageConverter](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)