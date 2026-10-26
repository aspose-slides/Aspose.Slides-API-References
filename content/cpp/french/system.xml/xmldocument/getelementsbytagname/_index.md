---
title: GetElementsByTagName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un XmlNodeList contenant une liste de tous les éléments descendants correspondant au nom spécifié.
type: docs
weight: 443
url: /fr/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) méthode


Renvoie un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les éléments descendants correspondant au nom spécifié.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié à correspondre. Il est comparé à la valeur **get_Name** du nœud correspondant. La valeur spéciale **"*"** correspond à toutes les balises. |

### Valeur de retour

Un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les nœuds correspondants. Si aucun nœud ne correspond **name**, la collection renvoyée sera vide.

## XmlDocument::GetElementsByTagName(String, String) méthode


Renvoie un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les éléments descendants correspondant aux [XmlDocument::get_LocalName](../get_localname/) et [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) spécifiés.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le LocalName à correspondre. La valeur spéciale **"*"** correspond à toutes les balises. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI à correspondre. |

### Valeur de retour

Un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les nœuds correspondants. Si aucun nœud ne correspond aux **localName** et **namespaceURI** spécifiés, la collection renvoyée sera vide.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)