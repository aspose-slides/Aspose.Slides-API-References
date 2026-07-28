---
title: XPathDocument()
second_title: Aspose.Slides for C++ API referencia
description: Új példányt hoz létre a XPathDocument osztályból a megadott XmlReader objektumban található XML adatokból.
type: docs
weight: 1
url: /hu/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor


Inicializál egy új [XPathDocument](../) osztálypéldányt a megadott [XmlReader](../../../system.xml/xmlreader/) objektumban található XML adatokból.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | A [XmlReader](../../../system.xml/xmlreader/) objektum, amely tartalmazza az XML adatokat. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor


Inicializál egy új [XPathDocument](../) osztálypéldányt a megadott [XmlReader](../../../system.xml/xmlreader/) objektumban található XML adatokból a megadott szóközkezeléssel.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | A [XmlReader](../../../system.xml/xmlreader/) objektum, amely tartalmazza az XML adatokat. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Egy XmlSpace objektum. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor


Inicializál egy új [XPathDocument](../) osztálypéldányt a megadott TextReader objektumban található XML adatokból.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | A TextReader objektum, amely tartalmazza az XML adatokat. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor


Inicializál egy új [XPathDocument](../) osztálypéldányt a megadott Stream objektumban található XML adatokból.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A Stream objektum, amely tartalmazza az XML adatokat. |

## XPathDocument::XPathDocument(const String\&) constructor


Inicializál egy új [XPathDocument](../) osztálypéldányt a megadott fájlban található XML adatokból.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | A fájl elérési útja, amely az XML adatokat tartalmazza. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor


Inicializál egy új [XPathDocument](../) osztálypéldányt a megadott fájlban található XML adatokból a megadott szóközkezeléssel.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | A fájl elérési útja, amely az XML adatokat tartalmazza. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Egy XmlSpace objektum. |

## Lásd még

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)