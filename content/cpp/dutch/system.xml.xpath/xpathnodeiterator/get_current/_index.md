---
title: get_Current()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, haalt het XPathNavigator-object voor dit XPathNodeIterator op, gepositioneerd op de huidige contextnode.
type: docs
weight: 1
url: /nl/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() methode

Wanneer overschreven in een afgeleide klasse, haalt het [XPathNavigator](../../xpathnavigator/)-object voor deze [XPathNodeIterator](../) op, gepositioneerd op de huidige contextnode.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Retourwaarde

Een [XPathNavigator](../../xpathnavigator/)-object gepositioneerd op de contextnode waaruit de knoopset werd geselecteerd. De [XPathNodeIterator::MoveNext](../movenext/)-methode moet worden aangeroepen om de [XPathNodeIterator](../) naar de eerste knoop in de geselecteerde set te verplaatsen.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../../xpathnavigator/)
* Klasse [XPathNodeIterator](../)
* Naamruimte [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)