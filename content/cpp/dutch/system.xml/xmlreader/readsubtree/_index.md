---
title: ReadSubtree()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een nieuwe XmlReader instantie die kan worden gebruikt om het huidige knooppunt en al zijn afstammelingen te lezen.
type: docs
weight: 963
url: /nl/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() methode

Retourneert een nieuw [XmlReader](../)-instantie die kan worden gebruikt om het huidige knooppunt en al zijn afstammelingen te lezen.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Retourwaarde

Een nieuwe XML-lezer-instantie ingesteld op [ReadState::Initial](../../readstate/). Het aanroepen van de [XmlReader::Read](../read/)-methode positioneert de nieuwe lezer op het knooppunt dat actueel was vóór de aanroep van de [XmlReader::ReadSubtree](./)-methode.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)