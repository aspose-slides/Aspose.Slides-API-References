---
title: ValidateElement()
second_title: Aspose.Slides for C++ API 參考
description: 驗證當前上下文中的元素。
type: docs
weight: 131
url: /zh-hant/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String&, const String&, const SharedPtr<XmlSchemaInfo>&) 方法

驗證當前上下文中的元素。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | 要驗證的元素的本地名稱。 |
| namespaceUri | const [String](../../../system/string/)& | 要驗證的元素的命名空間 URI。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | 在成功驗證元素名稱後，其屬性將被設定的 [XmlSchemaInfo](../../xmlschemainfo/) 物件。此參數可為 **nullptr**。 |

## XmlSchemaValidator::ValidateElement(const String&, const String&, const SharedPtr<XmlSchemaInfo>&, const String&, const String&, const String&, const String&) 方法

使用指定的 **xsi:Type**、**xsi:Nil**、**xsi:SchemaLocation** 與 **xsi:NoNamespaceSchemaLocation** 屬性值，驗證當前上下文中的元素。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | 要驗證的元素的本地名稱。 |
| namespaceUri | const [String](../../../system/string/)& | 要驗證的元素的命名空間 URI。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | 在成功驗證元素名稱後，其屬性將被設定的 [XmlSchemaInfo](../../xmlschemainfo/) 物件。此參數可為 **nullptr**。 |
| xsiType | const [String](../../../system/string/)& | 元素的 **xsi:Type** 屬性值。此參數可為 **nullptr**。 |
| xsiNil | const [String](../../../system/string/)& | 元素的 **xsi:Nil** 屬性值。此參數可為 **nullptr**。 |
| xsiSchemaLocation | const [String](../../../system/string/)& | 元素的 **xsi:SchemaLocation** 屬性值。此參數可為 **nullptr**。 |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)& | 元素的 **xsi:NoNamespaceSchemaLocation** 屬性值。此參數可為 **nullptr**。 |

## 參見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSchemaInfo](../../xmlschemainfo/)
* 類別 [XmlSchemaValidator](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)