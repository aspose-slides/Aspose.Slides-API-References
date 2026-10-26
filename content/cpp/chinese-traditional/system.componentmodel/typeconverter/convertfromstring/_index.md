---
title: ConvertFromString()
second_title: Aspose.Slides for C++ API 參考
description: 將字串轉換為物件。
type: docs
weight: 40
url: /zh-hant/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) 方法

將字串轉換為物件。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 要轉換的值。 |

### 返回值

已轉換的物件。

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) 方法

將字串轉換為物件。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| text | const [System::String](../../../system/string/)\& | 要轉換的值。 |

### 返回值

已轉換的物件。

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) 方法

將字串轉換為物件。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 轉換物件時使用的文化。 |
| text | const [System::String](../../../system/string/)\& | 要轉換的值。 |

### 返回值

已轉換的物件。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [String](../../../system/string/)
* 類別 [TypeConverter](../)
* 類別 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System::ComponentModel](../../)
* 函式庫 [Aspose.Slides](../../../)