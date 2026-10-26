---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: "Liest ein XML-Schema aus dem bereitgestellten IO::TextReader."
type: docs
weight: 365
url: /de/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) Methode

Liest ein XML [Schema](../../) aus dem bereitgestellten [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der [IO::TextReader](../../../system.io/textreader/) enthält das XML [Schema](../../), das gelesen werden soll. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Der Validierungsereignishandler, der Informationen über die XML [Schema](../../) Syntaxfehler erhält. |

### Rückgabewert

Das [XmlSchema](../)-Objekt, das das XML [Schema](../../) darstellt.

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) Methode

Liest ein XML [Schema](../../) aus dem bereitgestellten Stream.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der bereitgestellte Datenstream. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Der Validierungsereignishandler, der Informationen über die XML [Schema](../../) Syntaxfehler erhält. |

### Rückgabewert

Das [XmlSchema](../)-Objekt, das das XML [Schema](../../) darstellt.

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) Methode

Liest ein XML [Schema](../../) aus dem bereitgestellten [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Der [XmlReader](../../../system.xml/xmlreader/) enthält das XML [Schema](../../), das gelesen werden soll. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Der Validierungsereignishandler, der Informationen über die XML [Schema](../../) Syntaxfehler erhält. |

### Rückgabewert

Das [XmlSchema](../)-Objekt, das das XML [Schema](../../) darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)