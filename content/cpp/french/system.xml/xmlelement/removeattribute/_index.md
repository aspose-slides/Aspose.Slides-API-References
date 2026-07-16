---
title: RemoveAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime un attribut par son nom.
type: docs
weight: 235
url: /fr/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) méthode

Supprime un attribut par son nom.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de l'attribut à supprimer. Il s'agit d'un nom qualifié. Il est comparé à la valeur **get_Name** du nœud correspondant. |

## XmlElement::RemoveAttribute(String, String) méthode

Supprime un attribut avec le nom local et l'URI d'espace de noms spécifiés. (Si l'attribut supprimé a une valeur par défaut, elle est immédiatement remplacée).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut à supprimer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut à supprimer. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)