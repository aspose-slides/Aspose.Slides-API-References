---
title: get_Current()
second_title: Aspose.Slides for C++ API-referencia
description: Amikor felül van írva egy leszármazott osztályban, visszaadja az XPathNavigator objektumot ehhez az XPathNodeIterator-hez, amely az aktuális kontextuscsomópontra van pozicionálva.
type: docs
weight: 1
url: /hu/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metódus

Ha felül van írva egy leszármazott osztályban, visszaadja a(z) [XPathNavigator](../../xpathnavigator/) objektumot ehhez a [XPathNodeIterator](../)-hez, amely az aktuális kontextuscsomópontra van pozicionálva.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Visszatérési érték

Egy [XPathNavigator](../../xpathnavigator/) objektum, amely a kontextuscsomópontra van pozicionálva, ahonnan a csomóponthalmaz ki lett választva. A(z) [XPathNodeIterator::MoveNext](../movenext/) metódust meg kell hívni a(z) [XPathNodeIterator](../) áthelyezéséhez az első csomópontra a kiválasztott halmazban.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XPathNavigator](../../xpathnavigator/)
* Osztály [XPathNodeIterator](../)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)