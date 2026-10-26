---
title: MoveToFirstNamespace()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, déplace le XPathNavigator vers le premier nœud d'espace de noms correspondant à l'XPathNamespaceScope spécifié.
type: docs
weight: 560
url: /fr/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) méthode

Lorsqu'elle est remplacée dans une classe dérivée, déplace le [XPathNavigator](../) vers le premier nœud d'espace de noms correspondant à l'XPathNamespaceScope spécifié.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Une valeur XPathNamespaceScope décrivant la portée de l'espace de noms. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le premier nœud d'espace de noms ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## XPathNavigator::MoveToFirstNamespace() méthode

Déplace le [XPathNavigator](../) vers le premier nœud d'espace de noms du nœud actuel.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers le premier nœud d'espace de noms ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Énumération [XPathNamespaceScope](../../xpathnamespacescope/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)