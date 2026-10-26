---
title: GetAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne la valeur de l'attribut avec le nom local et l'URI d'espace de noms spécifiés.
type: docs
weight: 482
url: /fr/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) méthode


Returns the value of the attribute with the specified local name and namespace URI.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. **localName** est sensible à la casse. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

Un [String](../../../system/string/) qui contient la valeur de l'attribut spécifié ; [String::Empty](../../../system/string/empty/) si aucun attribut correspondant n'est trouvé, ou si le [XPathNavigator](../) n'est pas positionné sur un nœud d'élément.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)