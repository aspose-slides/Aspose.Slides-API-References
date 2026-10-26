---
title: Serialize()
second_title: Aspose.Slides für C++ API-Referenz
description: Serialisiert das Dokument in XML.
type: docs
weight: 27
url: /de/system.xml.serialization/xmlserializer/serialize/
---
## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Namespace-Speicher. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Namespace-Speicher. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Namespace-Speicher. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Namespace-Speicher. |
| encodingStyle | [String](../../../system/string/) | Stil, der beim Serialisieren des Objekts verwendet wird. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) Methode

Serialisiert das Dokument in XML.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle, String id)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Zielstream. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) zu serialisieren. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Namespace-Speicher. |
| encodingStyle | [String](../../../system/string/) | Stil, der beim Serialisieren des Objekts verwendet wird. |
| id | [String](../../../system/string/) | [Object](../../../system/object/) ID, die beim Serialisieren verwendet wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [Object](../../../system/object/)
* Klasse [XmlSerializer](../)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XmlSerializerNamespaces](../../xmlserializernamespaces/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::Serialization](../../)
* Bibliothek [Aspose.Slides](../../../)