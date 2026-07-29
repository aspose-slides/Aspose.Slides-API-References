---
title: Select()
second_title: Aspose.Slides för C++ API-referens
description: Väljer en noduppsättning med det angivna XPath-uttrycket.
type: docs
weight: 794
url: /sv/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) metod

Väljer en noduppsättning med det angivna [XPath](../../)-uttrycket.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ett [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) metod

Väljer en noduppsättning med det angivna [XPath](../../)-uttrycket med [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som anges för att lösa namnrymdsprefix.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ett [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objekt som används för att lösa namnrymdsprefix. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) metod

Väljer en noduppsättning med det angivna [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ett [XPathExpression](../../xpathexpression/)-objekt som innehåller den kompilerade [XPath](../../)-frågan. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathNodeIterator](../../xpathnodeiterator/)
* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klass [XPathExpression](../../xpathexpression/)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)