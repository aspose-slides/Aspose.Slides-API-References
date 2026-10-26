---
title: Select()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert een knoopset met behulp van de opgegeven XPath-expressie.
type: docs
weight: 794
url: /nl/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) methode

Selecteert een knoopset met behulp van de opgegeven [XPath](../../) expressie.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Een [String](../../../system/string/) die een [XPath](../../) expressie voorstelt. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die naar de geselecteerde knoopset wijst.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) methode

Selecteert een knoopset met de opgegeven [XPath](../../) expressie en het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat is opgegeven om namespace-prefixen op te lossen.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Een [String](../../../system/string/) die een [XPath](../../) expressie voorstelt. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt om namespace-prefixen op te lossen. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die naar de geselecteerde knoopset wijst.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) methode

Selecteert een knoopset met de opgegeven [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Een [XPathExpression](../../xpathexpression/) object dat de gecompileerde [XPath](../../) query bevat. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die naar de geselecteerde knoopset wijst.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)