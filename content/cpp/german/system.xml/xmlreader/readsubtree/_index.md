---
title: ReadSubtree()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt eine neue XmlReader-Instanz zurück, die zum Lesen des aktuellen Knotens und aller seiner Nachkommen verwendet werden kann.
type: docs
weight: 963
url: /de/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() Methode

Gibt eine neue [XmlReader](../) Instanz zurück, die zum Lesen des aktuellen Knotens und aller seiner Nachkommen verwendet werden kann.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Rückgabewert

Eine neue XML-Leser-Instanz, die auf [ReadState::Initial](../../readstate/) gesetzt ist. Der Aufruf der [XmlReader::Read](../read/)-Methode positioniert den neuen Leser auf dem Knoten, der vor dem Aufruf der [XmlReader::ReadSubtree](./)-Methode aktuell war.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)