---
title: GetAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur de l'attribut avec le nom spécifié.
type: docs
weight: 209
url: /fr/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) méthode


Renvoie la valeur de l'attribut avec le nom spécifié.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de l'attribut à récupérer. Il s'agit d'un nom qualifié. Il est comparé à la valeur **get_Name** du nœud correspondant. |

### Valeur de retour

La valeur de l'attribut spécifié. Une chaîne vide est renvoyée si aucun attribut correspondant n'est trouvé ou si l'attribut n'a pas de valeur spécifiée ou par défaut.

## XmlElement::GetAttribute(String, String) méthode


Renvoie la valeur de l'attribut avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut à récupérer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut à récupérer. |

### Valeur de retour

La valeur de l'attribut spécifié. Une chaîne vide est renvoyée si aucun attribut correspondant n'est trouvé ou si l'attribut n'a pas de valeur spécifiée ou par défaut.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)