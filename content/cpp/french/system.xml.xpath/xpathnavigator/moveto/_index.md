---
title: MoveTo()
second_title: Référence de l'API Aspose.Slides for C++
description: Lorsqu'elle est remplacée dans une classe dérivée, déplace le XPathNavigator à la même position que le XPathNavigator spécifié.
type: docs
weight: 664
url: /fr/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) méthode

Lorsqu'elle est remplacée dans une classe dérivée, déplace le [XPathNavigator](../) à la même position que le [XPathNavigator](../) spécifié.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Le [XPathNavigator](../) positionné sur le nœud vers lequel vous souhaitez vous déplacer. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer à la même position que le [XPathNavigator](../) spécifié ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)