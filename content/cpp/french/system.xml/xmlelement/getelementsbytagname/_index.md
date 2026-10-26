---
title: GetElementsByTagName()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie une XmlNodeList contenant une liste de tous les éléments descendants qui correspondent au XmlElement::get_Name spécifié."
type: docs
weight: 287
url: /fr/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) méthode

Renvoie un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les éléments descendants qui correspondent au [XmlElement::get_Name](../get_name/) spécifié.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de balise à faire correspondre. Il s'agit d'un nom qualifié. Il est comparé à la valeur **get_Name** du nœud correspondant. L'astérisque (*) est une valeur spéciale qui correspond à toutes les balises. |

### Valeur de retour

Un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les nœuds correspondants. La liste est vide s'il n'y a aucun nœud correspondant.

## XmlElement::GetElementsByTagName(String, String) méthode

Renvoie un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les éléments descendants qui correspondent aux valeurs [XmlElement::get_LocalName](../get_localname/) et [XmlElement::get_NamespaceURI](../get_namespaceuri/) spécifiées.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local à faire correspondre. L'astérisque (*) est une valeur spéciale qui correspond à toutes les balises. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms à faire correspondre. |

### Valeur de retour

Un [XmlNodeList](../../xmlnodelist/) contenant une liste de tous les nœuds correspondants. La liste est vide s'il n'y a aucun nœud correspondant.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)