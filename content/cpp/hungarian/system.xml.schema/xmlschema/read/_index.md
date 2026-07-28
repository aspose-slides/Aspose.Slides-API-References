---
title: Read()
second_title: Aspose.Slides C++ API referencia
description: "XML sémát olvas be a megadott IO::TextReader-ből."
type: docs
weight: 365
url: /hu/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) metódus

XML [Schema](../../)-t olvas be a megadott [IO::TextReader](../../../system.io/textreader/)-ből.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | A [IO::TextReader](../../../system.io/textreader/) tartalmazza az olvasandó XML [Schema](../../)-t. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Az érvényesítési eseménykezelő, amely információt kap az XML [Schema](../../) szintaktikai hibáiról. |

### Visszatérési érték

A [XmlSchema](../) objektum, amely az XML [Schema](../../)-t képviseli.

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) metódus

XML [Schema](../../)-t olvas be a megadott adatfolyamból.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A megadott adatfolyam. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Az érvényesítési eseménykezelő, amely információt kap az XML [Schema](../../) szintaktikai hibáiról. |

### Visszatérési érték

A [XmlSchema](../) objektum, amely az XML [Schema](../../)-t képviseli.

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) metódus

XML [Schema](../../)-t olvas be a megadott [XmlReader](../../../system.xml/xmlreader/)-ból.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | A [XmlReader](../../../system.xml/xmlreader/) tartalmazza az olvasandó XML [Schema](../../)-t. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Az érvényesítési eseménykezelő, amely információt kap az XML [Schema](../../) szintaktikai hibáiról. |

### Visszatérési érték

A [XmlSchema](../) objektum, amely az XML [Schema](../../)-t képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Osztály [XmlSchema](../)
* Osztály [TextReader](../../../system.io/textreader/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)