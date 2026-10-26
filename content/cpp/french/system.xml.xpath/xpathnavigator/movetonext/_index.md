---
title: MoveToNext()
second_title: Référence API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, déplace le XPathNavigator vers le nœud frère suivant du nœud actuel.
type: docs
weight: 586
url: /fr/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() méthode

Lorsqu'elle est remplacée dans une classe dérivée, déplace le [XPathNavigator](../) vers le nœud frère suivant du nœud actuel.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud frère suivant ; sinon **false** s'il n'y a plus de frères ou si le [XPathNavigator](../) est actuellement positionné sur un nœud d'attribut. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## XPathNavigator::MoveToNext(String, String) méthode

Déplace le [XPathNavigator](../) vers le nœud frère suivant portant le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local du nœud frère suivant vers lequel se déplacer. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms du nœud frère suivant vers lequel se déplacer. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud frère suivant ; **false** s'il n'y a plus de frères, ou si le [XPathNavigator](../) est actuellement positionné sur un nœud d'attribut. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## XPathNavigator::MoveToNext(XPathNodeType) méthode

Déplace le [XPathNavigator](../) vers le nœud frère suivant du nœud actuel qui correspond au XPathNodeType spécifié.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType du nœud frère vers lequel se déplacer. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud frère suivant ; sinon **false** s'il n'y a plus de frères ou si le [XPathNavigator](../) est actuellement positionné sur un nœud d'attribut. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Enum [XPathNodeType](../../xpathnodetype/)
* classe [XPathNavigator](../)
* classe [String](../../../system/string/)
* espace de noms [System::Xml::XPath](../../)
* bibliothèque [Aspose.Slides](../../../)