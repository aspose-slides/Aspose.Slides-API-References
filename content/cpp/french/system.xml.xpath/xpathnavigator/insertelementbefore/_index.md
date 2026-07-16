---
title: InsertElementBefore()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouvel élément frère avant le nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés, avec la valeur spécifiée.
type: docs
weight: 1015
url: /fr/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) méthode

Crée un nouvel élément frère avant le nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés, avec la valeur indiquée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
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