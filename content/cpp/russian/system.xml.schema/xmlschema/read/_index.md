---
title: Read()
second_title: Aspose.Slides для C++ справочник API
description: "Читает XML-схему из предоставленного IO::TextReader."
type: docs
weight: 365
url: /ru/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) метод


Читает XML [Schema](../../) из предоставленного [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Объект [IO::TextReader](../../../system.io/textreader/), содержащий XML [Schema](../../) для чтения. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Обработчик событий проверки, получающий информацию об ошибках синтаксиса XML [Schema](../../). |

### Возвращаемое значение

Объект [XmlSchema](../), представляющий XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) метод


Читает XML [Schema](../../) из предоставленного потока.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Предоставленный поток данных. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Обработчик событий проверки, получающий информацию об ошибках синтаксиса XML [Schema](../../). |

### Возвращаемое значение

Объект [XmlSchema](../), представляющий XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) метод


Читает XML [Schema](../../) из предоставленного [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий XML [Schema](../../) для чтения. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Обработчик событий проверки, получающий информацию об ошибках синтаксиса XML [Schema](../../). |

### Возвращаемое значение

Объект [XmlSchema](../), представляющий XML [Schema](../../).

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [ValidationEventHandler](../../validationeventhandler/)
* Класс [XmlSchema](../)
* Класс [TextReader](../../../system.io/textreader/)
* Класс [Stream](../../../system.io/stream/)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)