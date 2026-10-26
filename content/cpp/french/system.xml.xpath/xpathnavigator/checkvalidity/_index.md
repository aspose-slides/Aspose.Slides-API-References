---
title: CheckValidity()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Vérifie que les données XML dans le XPathNavigator sont conformes au langage de définition XML Schema (XSD) fourni.
type: docs
weight: 755
url: /fr/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) méthode

Vérifie que les données XML dans le [XPathNavigator](../) sont conformes au langage de définition XML [Schema](../../../system.xml.schema/) (XSD) fourni.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | The XmlSchemaSet containing the schemas used to validate the XML data contained in the [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | The ValidationEventHandler that receives information about schema validation warnings and errors. |

### Valeur de retour

**true** if no schema validation errors occurred; otherwise, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Classe [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)