---
title: Deserialize()
second_title: Aspose.Slides voor C++ API-referentie
description: Deserialiseert XML-document naar een object.
type: docs
weight: 14
url: /nl/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) methode


Deserialiseert XML-document naar een object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Stream om document van te lezen. |

### Retourwaarde

[Object](../../../system/object/) dat eerder is geserialiseerd in het opgegeven document.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) methode


Deserialiseert XML-document naar een object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Reader om document van te lezen. |

### Retourwaarde

[Object](../../../system/object/) dat eerder is geserialiseerd in het opgegeven document.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) methode


Deserialiseert XML-document naar een object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader om document van te lezen. |

### Retourwaarde

[Object](../../../system/object/) dat eerder is geserialiseerd in het opgegeven document.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) methode


Deserialiseert XML-document naar een object.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader om document van te lezen. |
| encodingStyle | [String](../../../system/string/) | Stijl die wordt gebruikt om object te serialiseren. |

### Retourwaarde

[Object](../../../system/object/) dat eerder is geserialiseerd in het opgegeven document.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [XmlSerializer](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::Serialization](../../)
* Bibliotheek [Aspose.Slides](../../../)