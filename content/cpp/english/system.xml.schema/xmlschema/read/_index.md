---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: "Reads an XML Schema from the supplied IO::TextReader."
type: docs
weight: 365
url: /system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method


Reads an XML [Schema](../../) from the supplied [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The [IO::TextReader](../../../system.io/textreader/) containing the XML [Schema](../../) to read. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | The validation event handler that receives information about the XML [Schema](../../) syntax errors. |

### Return Value

The [XmlSchema](../) object representing the XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method


Reads an XML [Schema](../../) from the supplied stream.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The supplied data stream. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | The validation event handler that receives information about XML [Schema](../../) syntax errors. |

### Return Value

The [XmlSchema](../) object representing the XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method


Reads an XML [Schema](../../) from the supplied [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) containing the XML [Schema](../../) to read. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | The validation event handler that receives information about the XML [Schema](../../) syntax errors. |

### Return Value

The [XmlSchema](../) object representing the XML [Schema](../../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)