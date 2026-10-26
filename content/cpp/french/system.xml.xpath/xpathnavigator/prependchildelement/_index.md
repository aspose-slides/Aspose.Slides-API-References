---
title: PrependChildElement()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouvel élément enfant au début de la liste des nœuds enfants du nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée.
type: docs
weight: 989
url: /fr/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) méthode

Crée un nouvel élément enfant au début de la liste des nœuds enfants du nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Le préfixe d'espace de noms du nouvel élément enfant (le cas échéant). |
| localName | [String](../../../system/string/) | Le nom local du nouvel élément enfant (le cas échéant). |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms du nouvel élément enfant (le cas échéant). [String::Empty](../../../system/string/empty/) et **nullptr** sont équivalents. |
| value | [String](../../../system/string/) | La valeur du nouvel élément enfant. Si [String::Empty](../../../system/string/empty/) ou **nullptr** sont fournis, un élément vide est créé. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)