---
title: SelectDescendants()
second_title: Référence de l'API Aspose.Slides pour C++
description: Sélectionne tous les nœuds descendants du nœud actuel qui possèdent un XPathNodeType correspondant.
type: docs
weight: 859
url: /fr/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) méthode

Sélectionne tous les nœuds descendants du nœud actuel qui possèdent un XPathNodeType correspondant.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType des nœuds descendants. |
| matchSelf | **bool** | **true** pour inclure le nœud contextuel dans la sélection; sinon, **false**. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui contient les nœuds sélectionnés.

## XPathNavigator::SelectDescendants(String, String, bool) méthode

Sélectionne tous les nœuds descendants du nœud actuel dont le nom local et l'URI d'espace de noms sont spécifiés.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local des nœuds descendants. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms des nœuds descendants. |
| matchSelf | **bool** | **true** pour inclure le nœud contextuel dans la sélection; sinon, **false**. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui contient les nœuds sélectionnés.

## Voir aussi

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)