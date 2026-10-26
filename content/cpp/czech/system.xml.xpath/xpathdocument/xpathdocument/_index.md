---
title: XPathDocument()
second_title: Aspose.Slides pro C++ – reference API
description: Inicializuje novou instanci třídy XPathDocument z XML dat, která jsou obsažena ve specifikovaném objektu XmlReader.
type: docs
weight: 1
url: /cs/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

Inicializuje novou instanci třídy [XPathDocument](../) z XML dat, která jsou obsažena ve specifikovaném objektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/), který obsahuje XML data. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

Inicializuje novou instanci třídy [XPathDocument](../) z XML dat, která jsou obsažena ve specifikovaném objektu [XmlReader](../../../system.xml/xmlreader/) s určeným zacházením s bílými znaky.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/), který obsahuje XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Objekt XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

Inicializuje novou instanci třídy [XPathDocument](../) z XML dat, která jsou obsažena ve specifikovaném objektu TextReader.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Objekt TextReader, který obsahuje XML data. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

Inicializuje novou instanci třídy [XPathDocument](../) z XML dat ve specifikovaném objektu Stream.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Objekt Stream, který obsahuje XML data. |

## XPathDocument::XPathDocument(const String\&) constructor

Inicializuje novou instanci třídy [XPathDocument](../) z XML dat ve specifikovaném souboru.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Cesta k souboru, který obsahuje XML data. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

Inicializuje novou instanci třídy [XPathDocument](../) z XML dat v souboru, který je specifikován s určeným zacházením s bílými znaky.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Cesta k souboru, který obsahuje XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Objekt XmlSpace. |

## Viz také

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)