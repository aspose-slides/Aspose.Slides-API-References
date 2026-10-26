---
title: Deserialize()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Deserializuje XML dokument do objektu.
type: docs
weight: 14
url: /cs/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) metoda


Deserializuje XML dokument do objektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Datový proud pro načtení dokumentu. |

### Návratová hodnota

[Object](../../../system/object/) který byl dříve serializován do zadaného dokumentu.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) metoda


Deserializuje XML dokument do objektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Čtečka pro načtení dokumentu. |

### Návratová hodnota

[Object](../../../system/object/) který byl dříve serializován do zadaného dokumentu.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) metoda


Deserializuje XML dokument do objektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Čtečka pro načtení dokumentu. |

### Návratová hodnota

[Object](../../../system/object/) který byl dříve serializován do zadaného dokumentu.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) metoda


Deserializuje XML dokument do objektu.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Čtečka pro načtení dokumentu. |
| encodingStyle | [String](../../../system/string/) | Styl používaný k serializaci objektu. |

### Návratová hodnota

[Object](../../../system/object/) který byl dříve serializován do zadaného dokumentu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Stream](../../../system.io/stream/)
* Třída [XmlSerializer](../)
* Třída [TextReader](../../../system.io/textreader/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Třída [String](../../../system/string/)
* Obor názvů [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)