---
title: GetAttributeNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le XmlAttribute avec le nom spécifié.
type: docs
weight: 248
url: /fr/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) méthode

Renvoie le [XmlAttribute](../../xmlattribute/) avec le nom spécifié.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de l'attribut à récupérer. Il s'agit d'un nom qualifié. Il est comparé à la valeur **get_Name** du nœud correspondant. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) spécifié ou **nullptr** si aucun attribut correspondant n'a été trouvé.

## XmlElement::GetAttributeNode(String, String) méthode

Renvoie le [XmlAttribute](../../xmlattribute/) avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) spécifié ou **nullptr** si aucun attribut correspondant n'a été trouvé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)