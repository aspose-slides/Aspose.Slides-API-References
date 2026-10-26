---
title: ReadNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een XmlNode-object aan op basis van de informatie in de XmlReader. De lezer moet gepositioneerd zijn op een knooppunt of attribuut.
type: docs
weight: 495
url: /nl/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) methode

Maakt een [XmlNode](../../xmlnode/) object aan op basis van de informatie in de [XmlReader](../../xmlreader/). De lezer moet gepositioneerd zijn op een knooppunt of attribuut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | De XML-bron. |

### Retourwaarde

Het nieuwe [XmlNode](../../xmlnode/) of **nullptr** als er geen knooppunten meer zijn.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlReader](../../xmlreader/)
* Klasse [XmlDocument](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)