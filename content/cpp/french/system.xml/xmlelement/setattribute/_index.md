---
title: SetAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la valeur de l'attribut avec le nom spécifié.
type: docs
weight: 222
url: /fr/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) méthode


Définit la valeur de l'attribut avec le nom spécifié.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom de l'attribut à créer ou modifier. Il s'agit d'un nom qualifié. Si le nom contient deux-points, il est analysé en composants de préfixe et de nom local. |
| value | [String](../../../system/string/) | La valeur à définir pour l'attribut. |

## XmlElement::SetAttribute(String, String, String) méthode


Définit la valeur de l'attribut avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |
| value | [String](../../../system/string/) | La valeur à définir pour l'attribut. |

### Valeur de retour

La valeur de l'attribut.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)