---
title: CreateAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un XmlAttribute avec le nom spécifié.
type: docs
weight: 274
url: /fr/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) méthode

Crée un [XmlAttribute](../../xmlattribute/) avec le nom spécifié.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom qualifié de l'attribut. Si le nom contient deux-points, la valeur [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflète la partie du nom précédant le premier deux-points et la valeur [XmlDocument::get_LocalName](../get_localname/) reflète la partie du nom suivant le premier deux-points. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) reste vide sauf si le préfixe est un préfixe intégré reconnu tel que **xmlns**. Dans ce cas, get_NamespaceURI a pour valeur [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Valeur de retour

Le nouveau [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) méthode

Crée un [XmlAttribute](../../xmlattribute/) avec le nom qualifié spécifié et [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Le nom qualifié de l'attribut. Si le nom contient un deux-points, la valeur [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflétera la partie du nom précédant le deux-points et la valeur [XmlDocument::get_LocalName](../get_localname/) reflétera la partie du nom suivant le deux-points. |
| namespaceURI | const [String](../../../system/string/)\& | Le namespaceURI de l'attribut. Si le nom qualifié inclut un préfixe **xmlns**, alors ce paramètre doit être [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Valeur de retour

Le nouveau [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) méthode

Crée un [XmlAttribute](../../xmlattribute/) avec le [XmlNode::get_Prefix](../../xmlnode/get_prefix/) spécifié, le [XmlDocument::get_LocalName](../get_localname/) et le [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe de l'attribut (le cas échéant). [String::Empty](../../../system/string/empty/) et **nullptr** sont équivalents. |
| localName | const [String](../../../system/string/)\& | Le nom local de l'attribut. |
| namespaceURI | const [String](../../../system/string/)\& | Le URI de l'espace de noms de l'attribut (le cas échéant). [String::Empty](../../../system/string/empty/) et **nullptr** sont équivalents. Si **prefix** est **xmlns**, alors ce paramètre doit être [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) sinon une exception est levée. |

### Valeur de retour

Le nouveau [XmlAttribute](../../xmlattribute/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)