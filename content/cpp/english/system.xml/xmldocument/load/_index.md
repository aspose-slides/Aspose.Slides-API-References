---
title: Load()
second_title: Aspose.Slides for C++ API Reference
description: Loads the XML document from the specified URL.
type: docs
weight: 508
url: /system.xml/xmldocument/load/
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

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | There is a load or parse error in the XML. In this case, a FileNotFoundException is raised. |
| ArgumentException | **filename** is a zero-length string, contains only white space, or contains one or more invalid characters as defined by [System::IO::Path::GetInvalidPathChars](../../../system.io/path/getinvalidpathchars/). |
| ArgumentNullException | **filename** is **nullptr**. |
| PathTooLongException | The specified path, file name, or both exceed the system-defined maximum length. |
| DirectoryNotFoundException | The specified path is invalid (for example, it is on an unmapped drive). |
| IOException | An I/O error occurred while opening the file. |
| UnauthorizedAccessException | **filename** specified a file that is read-only. This operation is not supported on the current platform. **filename** specified a directory. The caller does not have the required permission. |
| FileNotFoundException | The file specified in **filename** was not found. |
| NotSupportedException | **filename** is in an invalid format. |
| SecurityException | The caller does not have the required permission. |


## XmlDocument::Load(SharedPtr\<IO::Stream\>) method


Loads the XML document from the specified stream.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream containing the XML document to load. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | There is a load or parse error in the XML. In this case, a FileNotFoundException is raised. |


## XmlDocument::Load(SharedPtr\<IO::TextReader\>) method


Loads the XML document from the specified TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | The TextReader used to feed the XML data into the document. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | There is a load or parse error in the XML. In this case, the document remains empty. |


## XmlDocument::Load(SharedPtr\<XmlReader\>) method


Loads the XML document from the specified [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | The [XmlReader](../../xmlreader/) used to feed the XML data into the document. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | There is a load or parse error in the XML. In this case, the document remains empty. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../../xmlreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)