---
title: SelectSingleNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Sélectionne un nœud unique dans le XPathNavigator à l'aide de la requête XPath spécifiée.
type: docs
weight: 781
url: /fr/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) méthode

Sélectionne un nœud unique dans le [XPathNavigator](../) à l'aide de la requête [XPath](../../) spécifiée.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [String](../../../system/string/) representing an [XPath](../../) expression. |

### Valeur de retour

Un objet [XPathNavigator](../) qui contient le premier nœud correspondant à la requête [XPath](../../) spécifiée ; sinon, **nullptr** s'il n'y a aucun résultat de requête.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) méthode

Sélectionne un nœud unique dans l'objet [XPathNavigator](../) à l'aide de la requête [XPath](../../) spécifiée avec l'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indiqué pour résoudre les préfixes d'espace de noms.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [String](../../../system/string/) representing an [XPath](../../) expression. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes in the [XPath](../../) query. |

### Valeur de retour

Un objet [XPathNavigator](../) qui contient le premier nœud correspondant à la requête [XPath](../../) spécifiée ; sinon **nullptr** s'il n'y a aucun résultat de requête.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) méthode

Sélectionne un nœud unique dans le [XPathNavigator](../) à l'aide de l'objet [XPathExpression](../../xpathexpression/) spécifié.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | An [XPathExpression](../../xpathexpression/) object containing the compiled [XPath](../../) query. |

### Valeur de retour

Un objet [XPathNavigator](../) qui contient le premier nœud correspondant à la requête [XPath](../../) spécifiée ; sinon **nullptr** s'il n'y a aucun résultat de requête.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathExpression](../../xpathexpression/)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)