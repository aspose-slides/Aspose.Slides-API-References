---
title: Load()
second_title: Aspose.Slides for C++ API Reference
description: Loads the XML document from the specified URL.
type: docs
weight: 508
url: /cpp/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) method


Loads the XML document from the specified URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL for the file containing the XML document to load. The URL can be either a local file or an HTTP URL (a [Web](../../../system.web/) address). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) method


Loads the XML document from the specified stream.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream containing the XML document to load. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) method


Loads the XML document from the specified TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | The TextReader used to feed the XML data into the document. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) method


Loads the XML document from the specified [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | The [XmlReader](../../xmlreader/) used to feed the XML data into the document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../../xmlreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)