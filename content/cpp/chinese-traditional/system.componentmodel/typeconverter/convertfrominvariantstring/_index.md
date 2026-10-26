---
title: ConvertFromInvariantString()
second_title: Aspose.Slides for C++ API 參考
description: 將不變字串轉換為物件。
type: docs
weight: 27
url: /zh-hant/system.componentmodel/typeconverter/convertfrominvariantstring/
---
## TypeConverter::ConvertFromInvariantString(const System::String\&) 方法

將不變字串轉換為物件。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::String &text)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 要轉換的值。 |

### 傳回值

已轉換的物件。

## TypeConverter::ConvertFromInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) 方法

將不變字串轉換為物件。

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| text | const [System::String](../../../system/string/)\& | 要轉換的值。 |

### 傳回值

已轉換的物件。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [String](../../../system/string/)
* 類別 [TypeConverter](../)
* 類別 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 命名空間 [System::ComponentModel](../../)
* 函式庫 [Aspose.Slides](../../../)