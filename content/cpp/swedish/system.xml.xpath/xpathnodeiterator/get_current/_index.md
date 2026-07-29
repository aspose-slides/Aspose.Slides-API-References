---
title: get_Current()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass, hämtar den XPathNavigator-objektet för denna XPathNodeIterator, placerat på den aktuella kontextnoden.
type: docs
weight: 1
url: /sv/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metod

När den åsidosätts i en avledd klass, hämtar den [XPathNavigator](../../xpathnavigator/)-objektet för detta [XPathNodeIterator](../), placerat på den aktuella kontextnoden.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Returvärde

Ett [XPathNavigator](../../xpathnavigator/)-objekt placerat på kontextnoden från vilken noduppsättningen valdes. Metoden [XPathNodeIterator::MoveNext](../movenext/) måste anropas för att flytta [XPathNodeIterator](../) till den första noden i den valda uppsättningen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathNavigator](../../xpathnavigator/)
* Klass [XPathNodeIterator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)