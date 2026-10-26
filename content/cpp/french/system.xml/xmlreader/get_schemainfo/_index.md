---
title: get_SchemaInfo()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Renvoie les informations de schéma qui ont été assignées au nœud actuel à la suite de la validation du schéma.
type: docs
weight: 196
url: /fr/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() méthode

Renvoie les informations de schéma qui ont été attribuées au nœud actuel à la suite de la validation du schéma.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Valeur de retour

Un objet IXmlSchemaInfo contenant les informations de schéma pour le nœud actuel. [Schema](../../../system.xml.schema/) information peut être définie sur les éléments, les attributs ou sur les nœuds texte avec une valeur [XmlReader::get_ValueType](../get_valuetype/) non nulle. Si le nœud actuel n'est pas l'un des types de nœuds ci-above, ou si l'instance [XmlReader](../) ne rapporte pas d'informations de schéma, cette méthode renvoie **nullptr**. Si cette méthode est appelée depuis un objet [XmlTextReader](../../xmltextreader/) ou un objet [XmlValidatingReader](../../xmlvalidatingreader/), elle renvoie toujours **nullptr**. Ces implémentations [XmlReader](../) n'exposent pas les informations de schéma via la méthode get_SchemaInfo.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)