---
title: SelectChildren()
second_title: Reference de l'API Aspose.Slides pour C++
description: Sélectionne tous les nœuds enfants du nœud actuel dont le XPathNodeType correspond.
type: docs
weight: 833
url: /fr/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) méthode

Sélectionne tous les nœuds enfants du nœud actuel qui ont le XPathNodeType correspondant.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType des nœuds enfants. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui contient les nœuds sélectionnés.

## XPathNavigator::SelectChildren(String, String) méthode

Sélectionne tous les nœuds enfants du nœud actuel dont le nom local et l'URI d'espace de noms sont spécifiés.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local des nœuds enfants. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms des nœuds enfants. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui contient les nœuds sélectionnés.

## Voir aussi

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)