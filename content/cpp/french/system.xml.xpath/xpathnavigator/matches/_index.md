---
title: Matches()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si le nœud actuel correspond à l'expression XPathExpression spécifiée.
type: docs
weight: 820
url: /fr/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) méthode


Détermine si le nœud actuel correspond au [XPathExpression](../../xpathexpression/) spécifié.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un objet [XPathExpression](../../xpathexpression/) contenant l'expression [XPath](../../) compilée. |

### Valeur de retour

**true** si le nœud actuel correspond au [XPathExpression](../../xpathexpression/) ; sinon, **false**.

## XPathNavigator::Matches(String) méthode


Détermine si le nœud actuel correspond à l'expression [XPath](../../) spécifiée.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | L'expression [XPath](../../). |

### Valeur de retour

**true** si le nœud actuel correspond à l'expression [XPath](../../) spécifiée ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathExpression](../../xpathexpression/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)