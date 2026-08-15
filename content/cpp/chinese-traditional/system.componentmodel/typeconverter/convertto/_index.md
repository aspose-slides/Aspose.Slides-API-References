---
title: ConvertTo()
second_title: Aspose.Slides C++ API 參考文件
description: 將物件轉換為特定類型。
type: docs
weight: 53
url: /zh-hant/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 方法

將物件轉換為特定類型。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要轉換。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要轉換成的類型。 |

### 返回值

已轉換的物件。

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 方法

將物件轉換為特定類型。

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 轉換物件時使用的文化。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要轉換。 |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 要轉換成的類型。 |

### 返回值

已轉換的物件。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [TypeConverter](../)
* 類別 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System::ComponentModel](../../)
* 庫 [Aspose.Slides](../../../)