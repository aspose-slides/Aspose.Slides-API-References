---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API 參考
description: 驗證具有簡單內容的元素的文字內容是否符合其資料類型，並驗證當前元素的內容對於具有複雜內容的元素是否完整。
type: docs
weight: 209
url: /zh-hant/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) 方法

驗證具有簡單內容的元素的文字內容是否符合其資料類型，並驗證具有複雜內容的元素的內容是否完整。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一個 [XmlSchemaInfo](../../xmlschemainfo/) 物件，其屬性會在成功驗證元素後設定。此參數可以是 **nullptr**。 |

### 返回值

若元素具有簡單內容，則返回已解析且具類型的文字值。

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) 方法

驗證指定元素的文字內容是否符合其資料類型。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一個 [XmlSchemaInfo](../../xmlschemainfo/) 物件，其屬性會在成功驗證元素的文字內容後設定。此參數可以是 **nullptr**。 |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 元素的具類型文字內容。 |

### 返回值

元素已解析且具類型的簡單內容。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [XmlSchemaInfo](../../xmlschemainfo/)
* 類別 [XmlSchemaValidator](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)