---
title: XPathDocument()
second_title: Aspose.Slides для C++ справочник API
description: Инициализирует новый экземпляр класса XPathDocument из XML-данных, содержащихся в указанном объекте XmlReader.
type: docs
weight: 1
url: /ru/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

Инициализирует новый экземпляр класса [XPathDocument](../) из XML-данных, содержащихся в указанном объекте [XmlReader](../../../system.xml/xmlreader/).

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий XML-данные. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

Инициализирует новый экземпляр класса [XPathDocument](../) из XML-данных, содержащихся в указанном объекте [XmlReader](../../../system.xml/xmlreader/) с указанной обработкой пробельных символов.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий XML-данные. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Объект XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

Инициализирует новый экземпляр класса [XPathDocument](../) из XML-данных, содержащихся в указанном объекте TextReader.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Объект TextReader, содержащий XML-данные. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

Инициализирует новый экземпляр класса [XPathDocument](../) из XML-данных в указанном объекте Stream.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Объект Stream, содержащий XML-данные. |

## XPathDocument::XPathDocument(const String\&) constructor

Инициализирует новый экземпляр класса [XPathDocument](../) из XML-данных в указанном файле.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Путь к файлу, содержащему XML-данные. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

Инициализирует новый экземпляр класса [XPathDocument](../) из XML-данных в файле, указанном с заданной обработкой пробельных символов.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Путь к файлу, содержащему XML-данные. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Объект XmlSpace. |

## См. также

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)