---
title: XmlSchemaValidator()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av XmlSchemaValidator-klassen.
type: docs
weight: 92
url: /sv/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) konstruktor


Initierar en ny instans av klassen [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Ett [XmlNameTable](../../../system.xml/xmlnametable/)-objekt som innehåller element- och attributnamn som atomiserade strängar. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller XML [Schema](../../) Definition Language (XSD)-scheman som används för validering. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ett [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objekt som används för att lösa namnrymder som påträffas under validering. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Ett XmlSchemaValidationFlags-värde som specificerar alternativ för schemavalidering. |

## Se även

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNameTable](../../../system.xml/xmlnametable/)
* Klass [XmlSchemaSet](../../xmlschemaset/)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klass [XmlSchemaValidator](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)