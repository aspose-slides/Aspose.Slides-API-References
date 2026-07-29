---
title: ReadSubtree()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ny XmlReader-instans som kan användas för att läsa den aktuella noden och alla dess underordnade noder.
type: docs
weight: 963
url: /sv/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() metod

Returnerar en ny [XmlReader](../)-instans som kan användas för att läsa den aktuella noden och alla dess underordnade noder.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Returvärde

En ny XML-läsarinstans inställd på [ReadState::Initial](../../readstate/). Att anropa [XmlReader::Read](../read/)-metoden placerar den nya läsaren på den nod som var aktuell innan anropet till [XmlReader::ReadSubtree](./)-metoden.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)