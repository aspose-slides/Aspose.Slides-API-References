---
title: Deserialize()
second_title: Aspose.Slides für C++ API Referenz
description: Deserialisiert ein XML-Dokument in ein Objekt.
type: docs
weight: 14
url: /de/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) Methode


Deserialisiert ein XML-Dokument in ein Objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Stream zum Lesen des Dokuments. |

### Rückgabewert

[Object](../../../system/object/) die zuvor in das angegebene Dokument serialisiert wurde.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) Methode


Deserialisiert ein XML-Dokument in ein Objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Reader zum Lesen des Dokuments. |

### Rückgabewert

[Object](../../../system/object/) die zuvor in das angegebene Dokument serialisiert wurde.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) Methode


Deserialisiert ein XML-Dokument in ein Objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader zum Lesen des Dokuments. |

### Rückgabewert

[Object](../../../system/object/) die zuvor in das angegebene Dokument serialisiert wurde.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) Methode


Deserialisiert ein XML-Dokument in ein Objekt.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader zum Lesen des Dokuments. |
| encodingStyle | [String](../../../system/string/) | Stil, der zum Serialisieren des Objekts verwendet wird. |

### Rückgabewert

[Object](../../../system/object/) die zuvor in das angegebene Dokument serialisiert wurde.

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [XmlSerializer](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)