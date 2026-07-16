---
title: IsStartElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Appelle XmlReader::MoveToContent et teste si le nœud de contenu actuel est une balise d'ouverture ou une balise d'élément vide."
type: docs
weight: 885
url: /fr/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() méthode

Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Valeur de retour

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## XmlReader::IsStartElement(String) méthode

Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](../get_name/) value of the element found matches the given argument.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | La chaîne comparée à la valeur **Name** de l'élément trouvé. |

### Valeur de retour

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## XmlReader::IsStartElement(String, String) méthode

Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found match the given strings.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | La chaîne à comparer à la valeur **LocalName** de l'élément trouvé. |
| ns | [String](../../../system/string/) | La chaîne à comparer à la valeur **NamespaceURI** de l'élément trouvé. |

### Valeur de retour

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## Voir aussi

* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)