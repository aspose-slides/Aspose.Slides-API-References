---
title: SetNamedItem()
second_title: Référence API Aspose.Slides pour C++
description: "Ajoute un XmlNode en utilisant la valeur XmlNode::get_Name."
type: docs
weight: 27
url: /fr/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) méthode

Ajoute un [XmlNode](../../xmlnode/) en utilisant sa valeur [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Un [XmlNode](../../xmlnode/) à stocker dans le [XmlNamedNodeMap](../). Si un nœud portant ce nom est déjà présent dans la map, il est remplacé par le nouveau. |

### Valeur de retour

Si le **node** remplace un nœud existant portant le même nom, l’ancien nœud est renvoyé ; sinon, **nullptr** est renvoyé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNamedNodeMap](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)