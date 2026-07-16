---
title: HasAttribute()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si le nœud actuel possède un attribut portant le nom spécifié.
type: docs
weight: 300
url: /fr/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) method

Détermine si le nœud actuel possède un attribut portant le nom spécifié.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de l'attribut à rechercher. Il s'agit d'un nom qualifié. Il est comparé à la valeur **get_Name** du nœud correspondant. |

### Valeur de retour

**true** si le nœud actuel possède l'attribut spécifié ; sinon, **false**.

## XmlElement::HasAttribute(String, String) method

Détermine si le nœud actuel possède un attribut avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut à rechercher. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut à rechercher. |

### Valeur de retour

**true** si le nœud actuel possède l'attribut spécifié ; sinon, **false**.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)