---
title: XPathDocument()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy nową instancję klasy XPathDocument z danych XML zawartych w określonym obiekcie XmlReader.
type: docs
weight: 1
url: /pl/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) konstruktor

Tworzy nową instancję klasy [XPathDocument](../) z danych XML zawartych w określonym obiekcie [XmlReader](../../../system.xml/xmlreader/).

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający dane XML. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) konstruktor

Tworzy nową instancję klasy [XPathDocument](../) z danych XML zawartych w określonym obiekcie [XmlReader](../../../system.xml/xmlreader/) przy użyciu określonego sposobu obsługi białych znaków.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający dane XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Obiekt XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) konstruktor

Tworzy nową instancję klasy [XPathDocument](../) z danych XML zawartych w określonym obiekcie TextReader.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Obiekt TextReader zawierający dane XML. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) konstruktor

Tworzy nową instancję klasy [XPathDocument](../) z danych XML w określonym obiekcie Stream.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Obiekt Stream zawierający dane XML. |

## XPathDocument::XPathDocument(const String\&) konstruktor

Tworzy nową instancję klasy [XPathDocument](../) z danych XML w określonym pliku.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Ścieżka do pliku zawierającego dane XML. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) konstruktor

Tworzy nową instancję klasy [XPathDocument](../) z danych XML w pliku określonym przy określonej obsłudze białych znaków.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Ścieżka do pliku zawierającego dane XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Obiekt XmlSpace. |

## Zobacz także

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [XPathDocument](../)
* Klasa [TextReader](../../../system.io/textreader/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)