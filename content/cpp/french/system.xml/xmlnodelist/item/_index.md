---
title: Item()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère un nœud à l'index donné.
type: docs
weight: 14
url: /fr/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) méthode


Récupère un nœud à l'index donné.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro dans la liste de nœuds. |

### Valeur de retour

Le [XmlNode](../../xmlnode/) avec l'index spécifié dans la collection. Si **index** est supérieur ou égal au nombre de nœuds dans la liste, cela renvoie **nullptr**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeList](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)