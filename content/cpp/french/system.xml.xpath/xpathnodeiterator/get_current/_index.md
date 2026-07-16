---
title: get_Current()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, récupère l'objet XPathNavigator pour cet XPathNodeIterator, positionné sur le nœud contextuel actuel.
type: docs
weight: 1
url: /fr/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() méthode

Lorsqu'elle est redéfinie dans une classe dérivée, récupère l'objet [XPathNavigator](../../xpathnavigator/) pour ce [XPathNodeIterator](../), positionné sur le nœud contextuel actuel.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Valeur de retour

Un objet [XPathNavigator](../../xpathnavigator/) positionné sur le nœud contextuel à partir duquel l'ensemble de nœuds a été sélectionné. La méthode [XPathNodeIterator::MoveNext](../movenext/) doit être appelée pour déplacer le [XPathNodeIterator](../) vers le premier nœud de l'ensemble sélectionné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../../xpathnavigator/)
* Classe [XPathNodeIterator](../)
* Espace de noms [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)