---
title: ValidateAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 驗證當前元素上下文中的屬性名稱、名稱空間 URI 以及值。
type: docs
weight: 144
url: /zh-hant/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) 方法

驗證當前元素上下文中的屬性名稱、名稱空間 URI 以及值。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要驗證之屬性的本地名稱。 |
| namespaceUri | const [String](../../../system/string/)\& | 要驗證之屬性的名稱空間 URI。 |
| attributeValue | const [String](../../../system/string/)\& | 要驗證之屬性的值。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 在成功驗證屬性後，其屬性會被設定的 [XmlSchemaInfo](../../xmlschemainfo/) 物件。此參數可以是 **nullptr**。 |

### 回傳值

已驗證屬性的值。

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) 方法

驗證當前元素上下文中的屬性名稱、名稱空間 URI 以及值。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要驗證之屬性的本地名稱。 |
| namespaceUri | const [String](../../../system/string/)\& | 要驗證之屬性的名稱空間 URI。 |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | 用於傳遞屬性值的 XmlValueGetter 回呼，該值的類型與屬性的 XML [Schema](../../) 定義語言 (XSD) 類型相容。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 在成功驗證屬性後，其屬性會被設定的 [XmlSchemaInfo](../../xmlschemainfo/) 物件。此參數也可以是 **nullptr**。 |

### 回傳值

已驗證屬性的值。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* 類別 [Object](../../../system/object/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSchemaInfo](../../xmlschemainfo/)
* 類別 [XmlSchemaValidator](../)
* 命名空間 [System::Xml::Schema](../../)
* 程式庫 [Aspose.Slides](../../../)