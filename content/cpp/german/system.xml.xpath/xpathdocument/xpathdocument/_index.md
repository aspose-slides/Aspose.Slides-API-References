---
title: XPathDocument()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der XPathDocument Klasse aus den XML-Daten, die im angegebenen XmlReader-Objekt enthalten sind.
type: docs
weight: 1
url: /de/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) Konstruktor


Initialisiert eine neue Instanz der [XPathDocument](../) Klasse aus den XML-Daten, die im angegebenen [XmlReader](../../../system.xml/xmlreader/) Objekt enthalten sind.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Das [XmlReader](../../../system.xml/xmlreader/) Objekt, das die XML-Daten enthält. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) Konstruktor


Initialisiert eine neue Instanz der [XPathDocument](../) Klasse aus den XML-Daten, die im angegebenen [XmlReader](../../../system.xml/xmlreader/) Objekt enthalten sind, mit der angegebenen Behandlung von Leerzeichen.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Das [XmlReader](../../../system.xml/xmlreader/) Objekt, das die XML-Daten enthält. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Ein XmlSpace-Objekt. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) Konstruktor


Initialisiert eine neue Instanz der [XPathDocument](../) Klasse aus den XML-Daten, die im angegebenen TextReader-Objekt enthalten sind.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Das TextReader-Objekt, das die XML-Daten enthält. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) Konstruktor


Initialisiert eine neue Instanz der [XPathDocument](../) Klasse aus den XML-Daten im angegebenen Stream-Objekt.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Das Stream-Objekt, das die XML-Daten enthält. |

## XPathDocument::XPathDocument(const String\&) Konstruktor


Initialisiert eine neue Instanz der [XPathDocument](../) Klasse aus den XML-Daten in der angegebenen Datei.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Der Pfad der Datei, die die XML-Daten enthält. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) Konstruktor


Initialisiert eine neue Instanz der [XPathDocument](../) Klasse aus den XML-Daten in der Datei, wobei die angegebene Behandlung von Leerzeichen verwendet wird.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Der Pfad der Datei, die die XML-Daten enthält. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Ein XmlSpace-Objekt. |

## Siehe auch

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XPathDocument](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)