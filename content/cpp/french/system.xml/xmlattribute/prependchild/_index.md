---
title: PrependChild()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le nœud spécifié au début de la liste des nœuds enfants de ce nœud.
type: docs
weight: 261
url: /fr/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) méthode


Ajoute le nœud spécifié au début de la liste des nœuds enfants de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Le [XmlNode](../../xmlnode/) à ajouter. S'il s'agit d'un [XmlDocumentFragment](../../xmldocumentfragment/), le contenu entier du fragment de document est déplacé dans la liste des enfants de ce nœud. |

### Valeur de retour

Le [XmlNode](../../xmlnode/) ajouté.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)