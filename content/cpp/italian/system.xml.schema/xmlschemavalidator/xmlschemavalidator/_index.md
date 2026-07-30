---
title: XmlSchemaValidator()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe XmlSchemaValidator.
type: docs
weight: 92
url: /it/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) costruttore


Inizializza una nuova istanza della classe [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Un oggetto [XmlNameTable](../../../system.xml/xmlnametable/) contenente i nomi di elementi e attributi come stringhe atomizzate. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Un oggetto [XmlSchemaSet](../../xmlschemaset/) contenente gli schemi XML [Schema](../../) Definition Language (XSD) usati per la convalida. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Un oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere gli spazi dei nomi incontrati durante la convalida. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Un valore XmlSchemaValidationFlags che specifica le opzioni di convalida dello schema. |

## Vedi anche

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../../system.xml/xmlnametable/)
* Classe [XmlSchemaSet](../../xmlschemaset/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlSchemaValidator](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)