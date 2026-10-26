---
title: MoveToNextNamespace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, déplace le XPathNavigator vers le nœud d'espace de noms suivant correspondant au XPathNamespaceScope spécifié.
type: docs
weight: 573
url: /fr/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) méthode

Lorsqu'elle est remplacée dans une classe dérivée, déplace le [XPathNavigator](../) vers le nœud d'espace de noms suivant correspondant au XPathNamespaceScope spécifié.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Une valeur XPathNamespaceScope décrivant la portée de l'espace de noms. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud d'espace de noms suivant ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## XPathNavigator::MoveToNextNamespace() méthode

Déplace le [XPathNavigator](../) vers le nœud d'espace de noms suivant.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le nœud d'espace de noms suivant ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Énum [XPathNamespaceScope](../../xpathnamespacescope/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)