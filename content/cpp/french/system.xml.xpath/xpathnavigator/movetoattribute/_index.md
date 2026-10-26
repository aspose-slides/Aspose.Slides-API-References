---
title: MoveToAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace le XPathNavigator vers l'attribut dont le nom local et l'URI d'espace de noms correspondent.
type: docs
weight: 495
url: /fr/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) méthode

Déplace le [XPathNavigator](../) vers l'attribut dont le nom local et l'URI d'espace de noms correspondent.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut ; **nullptr** pour un espace de noms vide. |

### Valeur de retour

**true** si le [XPathNavigator](../) réussit à se déplacer vers l'attribut ; sinon, **false**. Si **false**, la position du [XPathNavigator](../) reste inchangée.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)