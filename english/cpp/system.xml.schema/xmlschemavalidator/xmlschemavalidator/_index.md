---
title: XmlSchemaValidator()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the XmlSchemaValidator class.
type: docs
weight: 92
url: /cpp/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor


Initializes a new instance of the [XmlSchemaValidator](../) class.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | An [XmlNameTable](../../../system.xml/xmlnametable/) object containing element and attribute names as atomized strings. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | An [XmlSchemaSet](../../xmlschemaset/) object containing the XML [Schema](../../) Definition Language (XSD) schemas used for validation. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | An [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used for resolving namespaces encountered during validation. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | An XmlSchemaValidationFlags value specifying schema validation options. |

## See Also

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)