---
title: Save()
second_title: Aspose.Slides for C++ API Reference
description: Saves the XML document to the specified file. If the specified file exists, this method overwrites it.
type: docs
weight: 534
url: /cpp/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) method


Saves the XML document to the specified file. If the specified file exists, this method overwrites it.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | The location of the file where you want to save the document. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) method


Saves the XML document to the specified stream.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream to which you want to save. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) method


Saves the XML document to the specified TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | The TextWriter to which you want to save. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) method


Saves the XML document to the specified [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | The [XmlWriter](../../xmlwriter/) to which you want to save. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)