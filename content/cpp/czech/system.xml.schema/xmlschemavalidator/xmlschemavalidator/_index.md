---
title: XmlSchemaValidator()
second_title: Aspose.Slides pro C++ API Reference
description: Inicializuje novou instanci třídy XmlSchemaValidator.
type: docs
weight: 92
url: /cs/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) konstruktor

Inicializuje novou instanci třídy [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Objekt [XmlNameTable](../../../system.xml/xmlnametable/) obsahující názvy elementů a atributů jako atomizované řetězce. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Objekt [XmlSchemaSet](../../xmlschemaset/) obsahující schémata XML [Schema](../../) Definition Language (XSD) používaná pro validaci. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný pro řešení oborů názvů, na které se narazí během validace. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Hodnota XmlSchemaValidationFlags určující možnosti validace schématu. |

## Viz také

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNameTable](../../../system.xml/xmlnametable/)
* Třída [XmlSchemaSet](../../xmlschemaset/)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XmlSchemaValidator](../)
* Obor názvů [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)