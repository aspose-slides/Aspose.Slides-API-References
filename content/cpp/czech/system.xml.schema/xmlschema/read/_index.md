---
title: Read()
second_title: Aspose.Slides pro C++ – reference API
description: "Načte XML schéma z poskytnutého IO::TextReaderu."
type: docs
weight: 365
url: /cs/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) metoda


Načte XML [Schema](../../) z poskytnutého [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/) obsahující XML [Schema](../../) k načtení. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Validátor událostí, který přijímá informace o syntaktických chybách XML [Schema](../../). |

### Návratová hodnota

[XmlSchema](../) objekt představující XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) metoda


Načte XML [Schema](../../) z poskytnutého proudu.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Poskytnutý datový proud. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Validátor událostí, který přijímá informace o syntaktických chybách XML [Schema](../../). |

### Návratová hodnota

[XmlSchema](../) objekt představující XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) metoda


Načte XML [Schema](../../) z poskytnutého [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující XML [Schema](../../) k načtení. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Validátor událostí, který přijímá informace o syntaktických chybách XML [Schema](../../). |

### Návratová hodnota

[XmlSchema](../) objekt představující XML [Schema](../../).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* třída [XmlSchema](../)
* třída [TextReader](../../../system.io/textreader/)
* třída [Stream](../../../system.io/stream/)
* třída [XmlReader](../../../system.xml/xmlreader/)
* jmenný prostor [System::Xml::Schema](../../)
* knihovna [Aspose.Slides](../../../)