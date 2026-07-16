---
title: SelectAncestors()
second_title: Référence de l'API Aspose.Slides for C++
description: Sélectionne tous les nœuds ancêtres du nœud actuel qui ont un XPathNodeType correspondant.
type: docs
weight: 846
url: /fr/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) méthode

Sélectionne tous les nœuds ancêtres du nœud actuel qui ont un XPathNodeType correspondant.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType des nœuds ancêtres. |
| matchSelf | **bool** | Pour inclure le nœud de contexte dans la sélection, **true** ; sinon, **false**. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui contient les nœuds sélectionnés. Les nœuds retournés sont dans l'ordre inverse du document.

## XPathNavigator::SelectAncestors(String, String, bool) méthode

Sélectionne tous les nœuds ancêtres du nœud actuel qui ont le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local des nœuds ancêtres. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms des nœuds ancêtres. |
| matchSelf | **bool** | Pour inclure le nœud de contexte dans la sélection, **true** ; sinon, **false**. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui contient les nœuds sélectionnés. Les nœuds retournés sont dans l'ordre inverse du document.

## Voir aussi

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)