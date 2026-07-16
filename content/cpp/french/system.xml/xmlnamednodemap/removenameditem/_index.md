---
title: RemoveNamedItem()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime le nœud du XmlNamedNodeMap.
type: docs
weight: 40
url: /fr/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) méthode

Supprime le nœud de [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié du nœud à supprimer. Le nom est comparé à la valeur [XmlNode::get_Name](../../xmlnode/get_name/) du nœud correspondant. |

### Valeur de retour

[XmlNode](../../xmlnode/) supprimé de ce [XmlNamedNodeMap](../) ou **nullptr** si aucun nœud correspondant n'a été trouvé.

## XmlNamedNodeMap::RemoveNamedItem(String, String) méthode

Supprime un nœud dont les valeurs [XmlNode::get_LocalName](../../xmlnode/get_localname/) et [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) correspondent.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local du nœud à supprimer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms du nœud à supprimer. |

### Valeur de retour

[XmlNode](../../xmlnode/) supprimé ou **nullptr** si aucun nœud correspondant n'a été trouvé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlNamedNodeMap](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)