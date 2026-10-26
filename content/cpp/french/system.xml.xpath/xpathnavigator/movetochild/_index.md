---
title: MoveToChild()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace le XPathNavigator vers le nœud enfant avec le nom local et l'URI d'espace de noms spécifiés.
type: docs
weight: 690
url: /fr/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) méthode

Déplace le [XPathNavigator](../) vers le nœud enfant avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local du nœud enfant vers lequel se déplacer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms du nœud enfant vers lequel se déplacer. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud enfant ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## XPathNavigator::MoveToChild(XPathNodeType) méthode

Déplace le [XPathNavigator](../) vers le nœud enfant du XPathNodeType spécifié.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType du nœud enfant vers lequel se déplacer. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud enfant ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)