---  
title: Item()  
second_title: Référence de l'API Aspose.Slides for C++  
description: Récupère le nœud à l'index spécifié dans le XmlNamedNodeMap.  
type: docs  
weight: 53  
url: /fr/system.xml/xmlnamednodemap/item/  
---
## XmlNamedNodeMap::Item(int32_t) méthode

Récupère le nœud à l'index spécifié dans le [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | La position d'index du nœud à récupérer depuis le [XmlNamedNodeMap](../). L'index commence à zéro ; ainsi, l'index du premier nœud est 0 et l'index du dernier nœud est [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Valeur de retour

Le [XmlNode](../../xmlnode/) à l'index spécifié. Si **index** est inférieur à 0 ou supérieur ou égal à la valeur [XmlNamedNodeMap::get_Count](../get_count/), **nullptr** est retourné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)