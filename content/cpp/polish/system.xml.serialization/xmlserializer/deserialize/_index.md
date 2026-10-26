---
title: Deserialize()
second_title: Aspose.Slides dla C++ API Reference
description: Deserializuje dokument XML do obiektu.
type: docs
weight: 14
url: /pl/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) metoda


Deserializuje dokument XML do obiektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień do odczytu dokumentu. |

### Wartość zwracana

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) metoda


Deserializuje dokument XML do obiektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Czytnik do odczytu dokumentu. |

### Wartość zwracana

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) metoda


Deserializuje dokument XML do obiektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Czytnik do odczytu dokumentu. |

### Wartość zwracana

[Object](../../../system/object/) that was previously serialized into the document given.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) metoda


Deserializuje dokument XML do obiektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Czytnik do odczytu dokumentu. |
| encodingStyle | [String](../../../system/string/) | Styl używany do serializacji obiektu. |

### Wartość zwracana

[Object](../../../system/object/) that was previously serialized into the document given.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [XmlSerializer](../)
* Klasa [TextReader](../../../system.io/textreader/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::Serialization](../../)
* Biblioteka [Aspose.Slides](../../../)