---
title: Evaluate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Évalue l'expression XPath spécifiée et renvoie le résultat typé.
type: docs
weight: 807
url: /fr/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) méthode


Évalue l'expression [XPath](../../) spécifiée et renvoie le résultat typé.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Une chaîne représentant une expression [XPath](../../) qui peut être évaluée. |

### Valeur de retour

Le résultat de l'expression ([Boolean](../../../system/boolean/), nombre, chaîne ou ensemble de nœuds). Cela correspond respectivement aux objets [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) méthode


Évalue l'expression [XPath](../../) spécifiée et renvoie le résultat typé, en utilisant l'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indiqué pour résoudre les préfixes d'espace de noms dans l'expression [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Une chaîne représentant une expression [XPath](../../) qui peut être évaluée. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilisé pour résoudre les préfixes d'espace de noms dans l'expression [XPath](../../). |

### Valeur de retour

Le résultat de l'expression ([Boolean](../../../system/boolean/), nombre, chaîne ou ensemble de nœuds). Cela correspond respectivement aux objets [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) méthode


Évalue le [XPathExpression](../../xpathexpression/) et renvoie le résultat typé.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) qui peut être évalué. |

### Valeur de retour

Le résultat de l'expression ([Boolean](../../../system/boolean/), nombre, chaîne ou ensemble de nœuds). Cela correspond respectivement aux objets [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) méthode


Utilise le contexte fourni pour évaluer le [XPathExpression](../../xpathexpression/) et renvoie le résultat typé.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) qui peut être évalué. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Un [XPathNodeIterator](../../xpathnodeiterator/) qui pointe vers l'ensemble de nœuds sélectionné sur lequel l'évaluation doit être effectuée. |

### Valeur de retour

Le résultat de l'expression ([Boolean](../../../system/boolean/), nombre, chaîne ou ensemble de nœuds). Cela correspond respectivement aux objets [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [Object](../../../system/object/)
* classe [String](../../../system/string/)
* classe [XPathNavigator](../)
* classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* classe [XPathExpression](../../xpathexpression/)
* classe [XPathNodeIterator](../../xpathnodeiterator/)
* espace de noms [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)