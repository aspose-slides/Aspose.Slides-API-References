---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: "Läser ett XML-schema från den levererade IO::TextReader."
type: docs
weight: 365
url: /sv/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) metod


Läser en XML [Schema](../../) från den levererade [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Det [IO::TextReader](../../../system.io/textreader/) som innehåller XML [Schema](../../) att läsa. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Valideringshändelsehanteraren som tar emot information om XML [Schema](../../) syntaxfel. |

### Returvärde

Objektet [XmlSchema](../) som representerar XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) metod


Läser en XML [Schema](../../) från den levererade strömmen.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Den levererade datastömmen. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Valideringshändelsehanteraren som tar emot information om XML [Schema](../../) syntaxfel. |

### Returvärde

Objektet [XmlSchema](../) som representerar XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) metod


Läser en XML [Schema](../../) från den levererade [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Det [XmlReader](../../../system.xml/xmlreader/) som innehåller XML [Schema](../../) att läsa. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Valideringshändelsehanteraren som tar emot information om XML [Schema](../../) syntaxfel. |

### Returvärde

Objektet [XmlSchema](../) som representerar XML [Schema](../../).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Klass [XmlSchema](../)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [Stream](../../../system.io/stream/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)