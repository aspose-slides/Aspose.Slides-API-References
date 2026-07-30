---
title: ReadSubtree()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací novou instanci XmlReader, která může být použita ke čtení aktuálního uzlu a všech jeho podřízených uzlů.
type: docs
weight: 963
url: /cs/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() metoda


Vrací novou [XmlReader](../) instanci, která může být použita ke čtení aktuálního uzlu a všech jeho podřízených uzlů.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### Návratová hodnota

Nová instance XML čtečky nastavená na [ReadState::Initial](../../readstate/). Volání metody [XmlReader::Read](../read/) umístí nového čtečku na uzel, který byl aktuální před voláním metody [XmlReader::ReadSubtree](./).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)