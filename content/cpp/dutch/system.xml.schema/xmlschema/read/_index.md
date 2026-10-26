---
title: Read()
second_title: Aspose.Slides voor C++ API Referentie
description: "Leest een XML-schema van de aangeleverde IO::TextReader."
type: docs
weight: 365
url: /nl/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) methode

Leest een XML [Schema](../../) van de meegeleverde [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De [IO::TextReader](../../../system.io/textreader/) die de XML [Schema](../../) bevat om te lezen. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | De validatie-eventhandler die informatie ontvangt over de XML [Schema](../../) syntaxisfouten. |

### Retourwaarde

Het [XmlSchema](../)-object dat de XML [Schema](../../) weergeeft.

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) methode

Leest een XML [Schema](../../) van de meegeleverde stream.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De meegeleverde gegevensstroom. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | De validatie-eventhandler die informatie ontvangt over XML [Schema](../../) syntaxisfouten. |

### Retourwaarde

Het [XmlSchema](../)-object dat de XML [Schema](../../) weergeeft.

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) methode

Leest een XML [Schema](../../) van de meegeleverde [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | De [XmlReader](../../../system.xml/xmlreader/) die de XML [Schema](../../) bevat om te lezen. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | De validatie-eventhandler die informatie ontvangt over de XML [Schema](../../) syntaxisfouten. |

### Retourwaarde

Het [XmlSchema](../)-object dat de XML [Schema](../../) weergeeft.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Klasse [XmlSchema](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Naamruimte [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)