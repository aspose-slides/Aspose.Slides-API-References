---
title: XmlSchemaValidator()
second_title: Aspose.Slides for C++ API 參考
description: 初始化 XmlSchemaValidator 類別的新執行個體。
type: docs
weight: 92
url: /zh-hant/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) 建構函式


初始化 [XmlSchemaValidator](../) 類別的新執行個體。

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | 一個 [XmlNameTable](../../../system.xml/xmlnametable/) 物件，包含作為原子化字串的元素和屬性名稱。 |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | 一個 [XmlSchemaSet](../../xmlschemaset/) 物件，包含用於驗證的 XML [Schema](../../) 定義語言 (XSD) 綱要。 |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 一個 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件，用於解析驗證期間遇到的名稱空間。 |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | 一個 XmlSchemaValidationFlags 值，指定綱要驗證選項。 |

## 另請參閱

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)