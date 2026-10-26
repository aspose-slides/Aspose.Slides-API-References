---
title: XmlSchemaValidator()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der XmlSchemaValidator-Klasse.
type: docs
weight: 92
url: /de/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) Konstruktor


Initialisiert eine neue Instanz der [XmlSchemaValidator](../)-Klasse.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Ein [XmlNameTable](../../../system.xml/xmlnametable/)-Objekt, das Element- und Attributnamen als atomarisierte Zeichenketten enthält. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Ein [XmlSchemaSet](../../xmlschemaset/)-Objekt, das die XML [Schema](../../) Definition Language (XSD)-Schemata enthält, die für die Validierung verwendet werden. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ein [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zum Auflösen von Namespaces verwendet wird, die während der Validierung auftreten. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Ein XmlSchemaValidationFlags-Wert, der Optionen für die Schemavalidierung angibt. |

## See Also

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNameTable](../../../system.xml/xmlnametable/)
* Klasse [XmlSchemaSet](../../xmlschemaset/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)