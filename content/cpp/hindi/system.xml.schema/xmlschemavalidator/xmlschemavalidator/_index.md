---
title: XmlSchemaValidator()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: XmlSchemaValidator क्लास का एक नया उदाहरण प्रारंभ करता है।
type: docs
weight: 92
url: /hi/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor

[XmlSchemaValidator](../) क्लास का एक नया उदाहरण प्रारंभ करता है।

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | An [XmlNameTable](../../../system.xml/xmlnametable/) object containing element and attribute names as atomized strings. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | An [XmlSchemaSet](../../xmlschemaset/) object containing the XML [Schema](../../) Definition Language (XSD) schemas used for validation. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | An [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used for resolving namespaces encountered during validation. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | An XmlSchemaValidationFlags value specifying schema validation options. |

## संबंधित देखें

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNameTable](../../../system.xml/xmlnametable/)
* क्लास [XmlSchemaSet](../../xmlschemaset/)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* क्लास [XmlSchemaValidator](../)
* नामस्थान [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)