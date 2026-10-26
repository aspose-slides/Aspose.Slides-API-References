---
title: Load()
second_title: Aspose.Slides für C++ API-Referenz
description: Lädt das XML-Dokument von der angegebenen URL.
type: docs
weight: 508
url: /de/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) Methode

Lädt das XML-Dokument von der angegebenen URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL für die Datei, die das zu ladende XML-Dokument enthält. Die URL kann entweder eine lokale Datei oder eine HTTP-URL (eine [Web](../../../system.web/)-Adresse) sein. |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) Methode

Lädt das XML-Dokument aus dem angegebenen Stream.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, der das zu ladende XML-Dokument enthält. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) Methode

Lädt das XML-Dokument aus dem angegebenen TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Der TextReader, der die XML-Daten in das Dokument einspeist. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) Methode

Lädt das XML-Dokument aus dem angegebenen [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Der [XmlReader](../../xmlreader/) verwendet, um die XML-Daten in das Dokument einzuspeisen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [XmlReader](../../xmlreader/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)