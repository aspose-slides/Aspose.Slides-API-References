---
title: get_Current()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird in einer abgeleiteten Klasse überschrieben, gibt das XPathNavigator-Objekt für diesen XPathNodeIterator zurück, das auf den aktuellen Kontextknoten positioniert ist.
type: docs
weight: 1
url: /de/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() Methode


Wenn in einer abgeleiteten Klasse überschrieben, gibt das [XPathNavigator](../../xpathnavigator/)-Objekt für dieses [XPathNodeIterator](../) zurück, das auf den aktuellen Kontextknoten positioniert ist.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### Rückgabewert

Ein [XPathNavigator](../../xpathnavigator/)-Objekt, das auf dem Kontextknoten positioniert ist, von dem die Knotengruppe ausgewählt wurde. Die [XPathNodeIterator::MoveNext](../movenext/)-Methode muss aufgerufen werden, um das [XPathNodeIterator](../) zum ersten Knoten im ausgewählten Satz zu bewegen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../../xpathnavigator/)
* Klasse [XPathNodeIterator](../)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)