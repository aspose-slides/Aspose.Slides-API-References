---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 參考
description: 將物件轉換為特定類型。
type: docs
weight: 14
url: /zh-hant/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 方法

將物件轉換為特定類型。

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 在轉換物件時使用的文化。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 要轉換的物件。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要轉換成的類型。 |

### 傳回值

已轉換的物件。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [FontConverter](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)