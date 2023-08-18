---
title: Deserialize()
second_title: Aspose.Slides for C++ API Reference
description: Deserializes XML document into object.
type: docs
weight: 14
url: /system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) method


Deserializes XML document into object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Stream to read document from. |

### Return Value

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) method


Deserializes XML document into object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Reader to read document from. |

### Return Value

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) method


Deserializes XML document into object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader to read document from. |

### Return Value

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) method


Deserializes XML document into object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader to read document from. |
| encodingStyle | [String](../../../system/string/) | Style used to serialize object. |

### Return Value

[Object](../../../system/object/) that was previously serialized into the document given.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlSerializer](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)