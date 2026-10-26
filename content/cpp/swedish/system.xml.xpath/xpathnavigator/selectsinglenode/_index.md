---
title: SelectSingleNode()
second_title: Aspose.Slides för C++ API-referens
description: Väljer en enskild nod i XPathNavigator med den angivna XPath-frågan.
type: docs
weight: 781
url: /sv/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metod

Väljer en enskild nod i [XPathNavigator](../) med den angivna [XPath](../../)-frågan.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | En [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |

### Returvärde

Ett [XPathNavigator](../)-objekt som innehåller den första matchande noden för den angivna [XPath](../../)-frågan; annars **nullptr** om det inte finns några resultat.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metod

Väljer en enskild nod i [XPathNavigator](../)-objektet med den angivna [XPath](../../)-frågan och det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objekt som anges för att lösa namnrymdsprefix.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | En [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objektet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) som används för att lösa namnrymdsprefix i [XPath](../../)-frågan. |

### Returvärde

Ett [XPathNavigator](../)-objekt som innehåller den första matchande noden för den angivna [XPath](../../)-frågan; annars **nullptr** om det inte finns några resultat.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metod

Väljer en enskild nod i [XPathNavigator](../) med det angivna [XPathExpression](../../xpathexpression/)-objektet.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ett [XPathExpression](../../xpathexpression/)-objekt som innehåller den kompilerade [XPath](../../)-frågan. |

### Returvärde

Ett [XPathNavigator](../)-objekt som innehåller den första matchande noden för den angivna [XPath](../../)-frågan; annars **nullptr** om det inte finns några resultat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klass [XPathExpression](../../xpathexpression/)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)