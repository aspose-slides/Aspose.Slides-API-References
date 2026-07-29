---
title: Load()
second_title: Aspose.Slides för C++ API-referens
description: Läser in XML-dokumentet från den angivna URL:en.
type: docs
weight: 508
url: /sv/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) metod

Laddar XML-dokumentet från den angivna URL:en.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL för filen som innehåller XML-dokumentet som ska laddas. URL:en kan vara antingen en lokal fil eller en HTTP-URL (en [Web](../../../system.web/) adress). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) metod

Laddar XML-dokumentet från den angivna strömmen.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strömmen som innehåller XML-dokumentet som ska laddas. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) metod

Laddar XML-dokumentet från den angivna TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader som används för att föra in XML-data i dokumentet. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) metod

Laddar XML-dokumentet från den angivna [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Den [XmlReader](../../xmlreader/) som används för att föra in XML-data i dokumentet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Klass [Stream](../../../system.io/stream/)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [XmlReader](../../xmlreader/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)