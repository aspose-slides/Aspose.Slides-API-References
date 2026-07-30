---
title: XPathDocument()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe XPathDocument dai dati XML contenuti nell'oggetto XmlReader specificato.
type: docs
weight: 1
url: /it/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) costruttore

Inizializza una nuova istanza della classe [XPathDocument](../) dai dati XML contenuti nell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) object that contains the XML data. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) costruttore

Inizializza una nuova istanza della classe [XPathDocument](../) dai dati XML contenuti nell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato con la gestione dello spazio bianco specificata.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) object that contains the XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | An XmlSpace object. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) costruttore

Inizializza una nuova istanza della classe [XPathDocument](../) dai dati XML contenuti nell'oggetto TextReader specificato.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The TextReader object that contains the XML data. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) costruttore

Inizializza una nuova istanza della classe [XPathDocument](../) dai dati XML contenuti nell'oggetto Stream specificato.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The Stream object that contains the XML data. |

## XPathDocument::XPathDocument(const String\&) costruttore

Inizializza una nuova istanza della classe [XPathDocument](../) dai dati XML contenuti nel file specificato.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | The path of the file that contains the XML data. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) costruttore

Inizializza una nuova istanza della classe [XPathDocument](../) dai dati XML contenuti nel file specificato con la gestione dello spazio bianco specificata.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | The path of the file that contains the XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | An XmlSpace object. |

## Vedi anche

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XPathDocument](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)