---
title: MoveToFirst()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace le XPathNavigator vers le premier nœud frère du nœud actuel.
type: docs
weight: 612
url: /fr/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() méthode

Déplace le [XPathNavigator](../) vers le premier nœud frère du nœud actuel.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le premier nœud frère du nœud actuel ; **false** s'il n'existe pas de premier frère, ou si le [XPathNavigator](../) est actuellement positionné sur un nœud d'attribut. Si le [XPathNavigator](../) est déjà positionné sur le premier frère, [XPathNavigator](../) renverra **true** et ne déplacera pas sa position. Si [XPathNavigator::MoveToFirst](./) renvoie **false** parce qu'il n'existe pas de premier frère, ou si [XPathNavigator](../) est actuellement positionné sur un attribut, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)