---
title: Save()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert das XML-Dokument in der angegebenen Datei. Wenn die angegebene Datei bereits existiert, überschreibt diese Methode sie.
type: docs
weight: 534
url: /de/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) Methode


Speichert das XML-Dokument in der angegebenen Datei. Wenn die angegebene Datei bereits existiert, überschreibt diese Methode sie.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Der Ort der Datei, in die Sie das Dokument speichern möchten. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) Methode


Speichert das XML-Dokument in den angegebenen Stream.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, in den Sie speichern möchten. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) Methode


Speichert das XML-Dokument in den angegebenen TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Der TextWriter, in den Sie speichern möchten. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) Methode


Speichert das XML-Dokument im angegebenen [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | Der [XmlWriter](../../xmlwriter/), in den Sie speichern möchten. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [XmlWriter](../../xmlwriter/)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)