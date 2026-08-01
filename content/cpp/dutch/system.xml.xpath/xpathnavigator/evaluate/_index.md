---
title: Evaluate()
second_title: Aspose.Slides voor C++ API-referentie
description: Evalueert de opgegeven XPath-expressie en retourneert het getypte resultaat.
type: docs
weight: 807
url: /nl/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) methode


Evalueert de opgegeven [XPath](../../) expressie en retourneert het getypte resultaat.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Een string die een [XPath](../../) expressie voorstelt die kan worden geëvalueerd. |

### Retourwaarde

Het resultaat van de expressie ([Boolean](../../../system/boolean/), getal, string of node set). Dit komt overeen met respectievelijk de objecten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) of [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) methode


Evalueert de opgegeven [XPath](../../) expressie en retourneert het getypte resultaat, met gebruik van het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat is opgegeven om namespace-prefixen in de [XPath](../../) expressie op te lossen.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Een string die een [XPath](../../) expressie voorstelt die kan worden geëvalueerd. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat wordt gebruikt om namespace-prefixen in de [XPath](../../) expressie op te lossen. |

### Retourwaarde

Het resultaat van de expressie ([Boolean](../../../system/boolean/), getal, string of node set). Dit komt overeen met respectievelijk de objecten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) of [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) methode


Evalueert de [XPathExpression](../../xpathexpression/) en retourneert het getypte resultaat.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Een [XPathExpression](../../xpathexpression/) die kan worden geëvalueerd. |

### Retourwaarde

Het resultaat van de expressie ([Boolean](../../../system/boolean/), getal, string of node set). Dit komt overeen met respectievelijk de objecten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) of [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) methode


Gebruikt de meegeleverde context om de [XPathExpression](../../xpathexpression/) te evalueren en retourneert het getypte resultaat.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Een [XPathExpression](../../xpathexpression/) die kan worden geëvalueerd. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Een [XPathNodeIterator](../../xpathnodeiterator/) die verwijst naar de geselecteerde node set waarop de evaluatie moet worden uitgevoerd. |

### Retourwaarde

Het resultaat van de expressie ([Boolean](../../../system/boolean/), getal, string of node set). Dit komt overeen met respectievelijk de objecten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) of [XPathNodeIterator](../../xpathnodeiterator/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)