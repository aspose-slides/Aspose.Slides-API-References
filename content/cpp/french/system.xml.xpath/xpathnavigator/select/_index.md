---
title: Select()
second_title: Référence de l'API Aspose.Slides pour C++
description: Sélectionne un ensemble de nœuds en utilisant l'expression XPath spécifiée.
type: docs
weight: 794
url: /fr/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) méthode

Sélectionne un ensemble de nœuds en utilisant l’expression [XPath](../../) spécifiée.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Une [String](../../../system/string/) représentant une expression [XPath](../../). |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) pointant vers l’ensemble de nœuds sélectionné.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) méthode

Sélectionne un ensemble de nœuds en utilisant l’expression [XPath](../../) spécifiée avec l’objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indiqué pour résoudre les préfixes d’espace de noms.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Une [String](../../../system/string/) représentant une expression [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L’objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilisé pour résoudre les préfixes d’espace de noms. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui pointe vers l’ensemble de nœuds sélectionné.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) méthode

Sélectionne un ensemble de nœuds en utilisant le [XPathExpression](../../xpathexpression/) spécifié.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un objet [XPathExpression](../../xpathexpression/) contenant la requête [XPath](../../) compilée. |

### Valeur de retour

Un [XPathNodeIterator](../../xpathnodeiterator/) qui pointe vers l’ensemble de nœuds sélectionné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)