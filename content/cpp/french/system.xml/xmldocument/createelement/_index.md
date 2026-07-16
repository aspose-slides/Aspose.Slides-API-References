---
title: CreateElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un élément avec le nom spécifié.
type: docs
weight: 339
url: /fr/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) méthode


Crée un élément avec le nom spécifié.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom qualifié de l'élément. Si le nom contient deux points alors la valeur [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflète la partie du nom précédant les deux points et la valeur [XmlDocument::get_LocalName](../get_localname/) reflète la partie du nom suivant les deux points. Le nom qualifié ne peut pas inclure de préfixe **xmlns**. |

### Valeur de retour

Le nouveau [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) méthode


Crée un [XmlElement](../../xmlelement/) avec le nom qualifié et [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Le nom qualifié de l'élément. Si le nom contient deux points alors la valeur [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflète la partie du nom précédant les deux points et la valeur [XmlDocument::get_LocalName](../get_localname/) reflète la partie du nom suivant les deux points. Le nom qualifié ne peut pas inclure de préfixe **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI d'espace de noms de l'élément. |

### Valeur de retour

Le nouveau [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) méthode


Crée un élément avec le [XmlNode::get_Prefix](../../xmlnode/get_prefix/) spécifié, le [XmlDocument::get_LocalName](../get_localname/) et le [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe du nouvel élément (le cas échéant). [String::Empty](../../../system/string/empty/) et **nullptr** sont équivalents. |
| localName | const [String](../../../system/string/)\& | Le nom local du nouvel élément. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI d'espace de noms du nouvel élément (le cas échéant). [String::Empty](../../../system/string/empty/) et **nullptr** sont équivalents. |

### Valeur de retour

Le nouveau [XmlElement](../../xmlelement/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlElement](../../xmlelement/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)