---
title: get_SchemaType()
second_title: Référence de l'API Aspose.Slides for C++
description: Renvoie un objet de type de schéma.
type: docs
weight: 287
url: /fr/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() méthode


Renvoie un objet de type de schéma.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### Valeur de retour

XmlSchemaDatatype, XmlSchemaSimpleType, ou XmlSchemaComplexType selon que la valeur du nœud est un type intégré XML [Schema](../../../system.xml.schema/) definition language (XSD) ou un simpleType ou complexType défini par l'utilisateur ; **nullptr** si le nœud actuel n'a pas de type de schéma.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)