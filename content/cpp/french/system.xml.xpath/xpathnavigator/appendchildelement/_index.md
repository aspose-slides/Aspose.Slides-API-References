---
title: AppendChildElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau nœud d'élément enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée.
type: docs
weight: 1002
url: /fr/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) méthode

Crée un nouveau nœud d'élément enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Le préfixe d'espace de noms du nouveau nœud d'élément enfant (le cas échéant). |
| localName | [String](../../../system/string/) | Le nom local du nouveau nœud d'élément enfant (le cas échéant). |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms du nouveau nœud d'élément enfant (le cas échéant). [String::Empty](../../../system/string/empty/) et **nullptr** sont équivalents. |
| value | [String](../../../system/string/) | La valeur du nouveau nœud d'élément enfant. Si [String::Empty](../../../system/string/empty/) ou **nullptr** sont fournis, un élément vide est créé. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)