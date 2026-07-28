---
title: Serialize()
second_title: Aspose.Slides for C++ API Referencia
description: A dokumentumot XML-be szerializálja.
type: docs
weight: 27
url: /hu/system.xml.serialization/xmlserializer/serialize/
---
## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Névtér tároló. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Névtér tároló. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Névtér tároló. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Névtér tároló. |
| encodingStyle | [String](../../../system/string/) | Stílus a objektum sorosítása során. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) method

A dokumentumot XML-be sorosít.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle, String id)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | Célfolyam. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) szerializálandó. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | Névtér tároló. |
| encodingStyle | [String](../../../system/string/) | Stílus a objektum sorosítása során. |
| id | [String](../../../system/string/) | [Object](../../../system/object/) azonosító a sorosításkor használatra. |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [Object](../../../system/object/)
* Osztály [XmlSerializer](../)
* Osztály [TextWriter](../../../system.io/textwriter/)
* Osztály [XmlWriter](../../../system.xml/xmlwriter/)
* Osztály [XmlSerializerNamespaces](../../xmlserializernamespaces/)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::Serialization](../../)
* Könyvtár [Aspose.Slides](../../../)