---
title: Load()
second_title: Aspose.Slides voor C++ API-referentie
description: Laadt het XML-document vanaf de opgegeven URL.
type: docs
weight: 508
url: /nl/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) methode

Laadt het XML-document vanaf de opgegeven URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL voor het bestand dat het XML-document bevat dat geladen moet worden. De URL kan zowel een lokaal bestand als een HTTP-URL zijn (een [Web](../../../system.web/) adres). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) methode

Laadt het XML-document vanaf de opgegeven stream.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stream die het XML-document bevat dat geladen moet worden. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) methode

Laadt het XML-document vanaf de opgegeven TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | De TextReader die wordt gebruikt om de XML-gegevens in het document te voeren. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) methode

Laadt het XML-document vanaf de opgegeven [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | De [XmlReader](../../xmlreader/) die wordt gebruikt om de XML-gegevens in het document te voeren. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [XmlReader](../../xmlreader/)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)