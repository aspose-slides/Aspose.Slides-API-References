---
title: XmlValidatingReader()
second_title: Aspose.Slides для C++ справочник API
description: Инициализирует новый экземпляр класса XmlValidatingReader, который проверяет содержимое, возвращаемое из указанного XmlReader.
type: docs
weight: 430
url: /ru/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) конструктор

Инициализирует новый экземпляр класса [XmlValidatingReader](../), который проверяет содержимое, возвращаемое из указанного [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/), из которого производится чтение во время проверки. Текущая реализация поддерживает только [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) конструктор

Инициализирует новый экземпляр класса [XmlValidatingReader](../) с указанными значениями.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Строка, содержащая XML-фрагмент для разбора. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML-фрагмента. Это также определяет, что может содержать строка фрагмента (см. таблицу ниже). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/), в которой будет разбирается XML-фрагмент. Это включает используемый [NameTable](../../nametable/), кодировку, область пространства имён, текущие области **xml:lang** и **xml:space**. |

## Примечания

В следующей таблице перечислены допустимые значения **fragType** и то, как читатель разбирает каждый из различных типов узлов.

| XmlNodeType | Фрагмент может содержать |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| The value of an attribute (the part inside the quotes). |
| Document| The contents of an entire XML document; this enforces document level rules. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) конструктор

Инициализирует новый экземпляр класса [XmlValidatingReader](../) с указанными значениями.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий XML-фрагмент для разбора. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML-фрагмента. Это определяет, что может содержать фрагмент (см. таблицу ниже). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/), в которой будет разбирается XML-фрагмент. Это включает используемый [XmlNameTable](../../xmlnametable/), кодировку, область пространства имён, текущие области **xml:lang** и **xml:space**. |

## Примечания

В следующей таблице перечислены допустимые значения **fragType** и то, как читатель разбирает каждый из различных типов узлов.

| XmlNodeType | Фрагмент может содержать |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| The value of an attribute (the part inside the quotes). |
| Document| The contents of an entire XML document; this enforces document level rules. |

## См. также

* Перечисление [XmlNodeType](../../xmlnodetype/)
* Тип определения [SharedPtr](../../../system/sharedptr/)
* Класс [XmlReader](../../xmlreader/)
* Класс [XmlValidatingReader](../)
* Класс [String](../../../system/string/)
* Класс [XmlParserContext](../../xmlparsercontext/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)