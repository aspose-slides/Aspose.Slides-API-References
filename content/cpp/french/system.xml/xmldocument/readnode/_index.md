---
title: ReadNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un objet XmlNode basé sur les informations contenues dans le XmlReader. Le lecteur doit être positionné sur un nœud ou un attribut.
type: docs
weight: 495
url: /fr/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) méthode

Crée un objet [XmlNode](../../xmlnode/) à partir des informations contenues dans le [XmlReader](../../xmlreader/). Le lecteur doit être positionné sur un nœud ou un attribut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | La source XML. |

### Valeur de retour

Le nouveau [XmlNode](../../xmlnode/) ou **nullptr** si aucun nœud supplémentaire n'existe.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlDocument](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)