---
title: CreateAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nœud d'attribut sur le nœud élément actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée.
type: docs
weight: 1041
url: /fr/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) méthode

Crée un nœud d'attribut sur le nœud élément actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Le préfixe d'espace de noms du nouveau nœud d'attribut (le cas échéant). |
| localName | [String](../../../system/string/) | Le nom local du nouveau nœud d'attribut qui ne peut pas [String::Empty](../../../system/string/empty/) ou **nullptr**. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms pour le nouveau nœud d'attribut (le cas échéant). |
| value | [String](../../../system/string/) | La valeur du nouveau nœud d'attribut. Si [String::Empty](../../../system/string/empty/) ou **nullptr** sont passés, un nœud d'attribut vide est créé. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)