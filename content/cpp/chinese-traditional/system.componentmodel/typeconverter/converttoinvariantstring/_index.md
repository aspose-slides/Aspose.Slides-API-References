---
title: ConvertToInvariantString()
second_title: Aspose.Slides for C++ API 參考
description: 將物件轉換為不變字串。
type: docs
weight: 66
url: /zh-hant/system.componentmodel/typeconverter/converttoinvariantstring/
---
## TypeConverter::ConvertToInvariantString(const System::SharedPtr\<System::Object\>\&) 方法

將物件轉換為不變字串。

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToInvariantString(const System::SharedPtr<System::Object> &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要轉換。 |

### 返回值

已轉換的物件。

## TypeConverter::ConvertToInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) 方法

將物件轉換為不變字串。

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 轉換上下文資訊。 |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 要轉換。 |

### 返回值

已轉換的物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeConverter](../)
* 類別 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 命名空間 [System::ComponentModel](../../)
* 函式庫 [Aspose.Slides](../../../)