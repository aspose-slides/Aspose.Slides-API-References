---
title: XmlSchemaValidator()
second_title: Aspose.Slides C++ API 参考
description: 初始化 XmlSchemaValidator 类的新实例。
type: docs
weight: 92
url: /zh/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor

初始化 [XmlSchemaValidator](../) 类的新实例。

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | An [XmlNameTable](../../../system.xml/xmlnametable/) object containing element and attribute names as atomized strings. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | An [XmlSchemaSet](../../xmlschemaset/) object containing the XML [Schema](../../) Definition Language (XSD) schemas used for validation. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | An [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used for resolving namespaces encountered during validation. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | An XmlSchemaValidationFlags value specifying schema validation options. |

## 另请参阅

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)