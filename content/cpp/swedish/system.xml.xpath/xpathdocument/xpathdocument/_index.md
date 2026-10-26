---
title: XPathDocument()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av klassen XPathDocument från XML-data som finns i det angivna XmlReader-objektet.
type: docs
weight: 1
url: /sv/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) konstruktor


Initierar en ny instans av klassen [XPathDocument](../) från XML-data som finns i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objektet [XmlReader](../../../system.xml/xmlreader/) som innehåller XML-data. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) konstruktor


Initierar en ny instans av klassen [XPathDocument](../) från XML-data som finns i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet med den angivna hanteringen av blanksteg.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objektet [XmlReader](../../../system.xml/xmlreader/) som innehåller XML-data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Ett XmlSpace-objekt. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) konstruktor


Initierar en ny instans av klassen [XPathDocument](../) från XML-data som finns i det angivna TextReader-objektet.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader-objektet som innehåller XML-data. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) konstruktor


Initierar en ny instans av klassen [XPathDocument](../) från XML-data i det angivna Stream-objektet.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream-objektet som innehåller XML-data. |

## XPathDocument::XPathDocument(const String\&) konstruktor


Initierar en ny instans av klassen [XPathDocument](../) från XML-data i den angivna filen.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Sökvägen till filen som innehåller XML-data. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) konstruktor


Initierar en ny instans av klassen [XPathDocument](../) från XML-data i den fil som anges med den angivna hanteringen av blanksteg.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Sökvägen till filen som innehåller XML-data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Ett XmlSpace-objekt. |

## Se även

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [XPathDocument](../)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [Stream](../../../system.io/stream/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)