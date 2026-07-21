---
title: XmlTextReader()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр класса XmlTextReader с указанным потоком.
type: docs
weight: 482
url: /ru/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным потоком.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий XML-данные для чтения. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным URL и потоком.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, используемый для разрешения внешних ресурсов. Свойство [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий XML-данные для чтения. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным потоком и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий XML-данные для чтения. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/), используемая при чтении. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным URL, потоком и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, используемый для разрешения внешних ресурсов. Свойство [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. Если **url** равно **nullptr**, **BaseURI** устанавливается в [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий XML-данные для чтения. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/), используемая при чтении. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader, содержащий XML-данные для чтения. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным URL и TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, используемый для разрешения внешних ресурсов. Свойство [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader, содержащий XML-данные для чтения. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным TextReader и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader, содержащий XML-данные для чтения. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/), используемая при чтении. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным URL, TextReader и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, используемый для разрешения внешних ресурсов. Свойство [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. Если **url** равно **nullptr**, **BaseURI** устанавливается в [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader, содержащий XML-данные для чтения. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/), используемая при чтении. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным потоком, типом XmlNodeType и [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий XML-фрагмент для разбора. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML-фрагмента. Также определяет, что может содержать фрагмент. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/), в котором будет разбираться **xmlFragment**. Включает используемый [XmlNameTable](../../xmlnametable/), кодировку, область видимости пространств имён, текущий **xml:lang** и область **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанной строкой, типом XmlNodeType и [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Строка, содержащая XML-фрагмент для разбора. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML-фрагмента. Также определяет, что может содержать строка-фрагмент. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/), в котором будет разбираться **xmlFragment**. Включает используемый [XmlNameTable](../../xmlnametable/), кодировку, область видимости пространств имён, текущий **xml:lang** и область **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным файлом.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL файла, содержащего XML-данные. Свойство [XmlTextReader::get_BaseURI](../get_baseuri/) устанавливается в это значение. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) конструктор


Создаёт новый экземпляр класса [XmlTextReader](../) с указанным файлом и [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL файла, содержащего XML-данные для чтения. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/), используемая при чтении. |

## Смотрите также

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)