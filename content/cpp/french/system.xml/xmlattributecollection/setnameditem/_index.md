---
title: SetNamedItem()
second_title: Référence de l'API Aspose.Slides for C++
description: "Ajoute un XmlNode en utilisant le résultat de XmlNode::get_Name."
type: docs
weight: 14
url: /fr/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) méthode

Ajoute un [XmlNode](../../xmlnode/) en utilisant son résultat [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Un noeud d'attribut à stocker dans cette collection. Le noeud sera ensuite accessible en utilisant le nom du noeud. Si un noeud portant ce nom est déjà présent dans la collection, il est remplacé par le nouveau ; sinon, le noeud est ajouté à la fin de la collection. |

### Valeur de retour

Si le **node** remplace un noeud existant portant le même nom, l'ancien noeud est renvoyé ; sinon, le noeud ajouté est renvoyé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttributeCollection](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)