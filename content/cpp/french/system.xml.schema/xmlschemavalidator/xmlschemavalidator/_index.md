---
title: XmlSchemaValidator()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe XmlSchemaValidator.
type: docs
weight: 92
url: /fr/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructeur


Initialise une nouvelle instance de la classe [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Un objet [XmlNameTable](../../../system.xml/xmlnametable/) contenant les noms d'éléments et d'attributs sous forme de chaînes atomisées. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Un objet [XmlSchemaSet](../../xmlschemaset/) contenant les schémas XML [Schema](../../) Definition Language (XSD) utilisés pour la validation. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Un objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilisé pour résoudre les espaces de noms rencontrés lors de la validation. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Une valeur XmlSchemaValidationFlags spécifiant les options de validation du schéma. |

## Voir aussi

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)