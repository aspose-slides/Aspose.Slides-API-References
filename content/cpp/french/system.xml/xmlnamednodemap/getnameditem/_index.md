---
title: GetNamedItem()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère un XmlNode spécifié par son nom.
type: docs
weight: 14
url: /fr/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) méthode

Récupère un [XmlNode](../../xmlnode/) spécifié par son nom.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié du nœud à récupérer. Il est comparé à la valeur [XmlNode::get_Name](../../xmlnode/get_name/) du nœud correspondant. |

### Valeur de retour

Un [XmlNode](../../xmlnode/) avec le nom spécifié ou **nullptr** si aucun nœud correspondant n’est trouvé.

## XmlNamedNodeMap::GetNamedItem(String, String) méthode

Récupère un nœud dont les valeurs [XmlNode::get_LocalName](../../xmlnode/get_localname/) et [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) correspondent.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local du nœud à récupérer. |
| namespaceURI | [String](../../../system/string/) | L’identifiant uniforme de ressource (URI) de l’espace de noms du nœud à récupérer. |

### Valeur de retour

Un [XmlNode](../../xmlnode/) avec le nom local et l’URI d’espace de noms correspondants ou **nullptr** si aucun nœud correspondant n’a été trouvé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlNamedNodeMap](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)