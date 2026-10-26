---
title: Matches()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om den aktuella noden matchar det angivna XPathExpression.
type: docs
weight: 820
url: /sv/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) metod

Bestämmer om den aktuella noden matchar den angivna [XPathExpression](../../xpathexpression/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ett [XPathExpression](../../xpathexpression/)-objekt som innehåller det kompilerade [XPath](../../)-uttrycket. |

### Returvärde

**true** om den aktuella noden matchar [XPathExpression](../../xpathexpression/); annars, **false**.

## XPathNavigator::Matches(String) metod

Bestämmer om den aktuella noden matchar den angivna [XPath](../../)-uttrycket.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Det [XPath](../../)-uttrycket. |

### Returvärde

**true** om den aktuella noden matchar det angivna [XPath](../../)-uttrycket; annars, **false**.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathExpression](../../xpathexpression/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)