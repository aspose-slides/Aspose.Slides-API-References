---
title: Deserialize()
second_title: Aspose.Slides för C++ API-referens
description: Deserialiserar XML-dokument till ett objekt.
type: docs
weight: 14
url: /sv/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) method

Deserialiserar XML-dokument till ett objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Ström att läsa dokumentet från. |

### Returvärde

[Object](../../../system/object/) som tidigare serialiserades till det angivna dokumentet.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) method

Deserialiserar XML-dokument till ett objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Läsare för att läsa dokumentet från. |

### Returvärde

[Object](../../../system/object/) som tidigare serialiserades till det angivna dokumentet.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) method

Deserialiserar XML-dokument till ett objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Läsare för att läsa dokumentet från. |

### Returvärde

[Object](../../../system/object/) som tidigare serialiserades till det angivna dokumentet.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) method

Deserialiserar XML-dokument till ett objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Läsare för att läsa dokumentet från. |
| encodingStyle | [String](../../../system/string/) | Stil som används för att serialisera objektet. |

### Returvärde

[Object](../../../system/object/) som tidigare serialiserades till det angivna dokumentet.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Stream](../../../system.io/stream/)
* Klass [XmlSerializer](../)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)