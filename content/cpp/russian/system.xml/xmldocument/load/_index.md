---
title: Load()
second_title: Справочник API Aspose.Slides для C++
description: Загружает XML-документ из указанного URL.
type: docs
weight: 508
url: /ru/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) метод

Загружает XML-документ из указанного URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL файла, содержащего XML-документ для загрузки. URL может быть как локальным файлом, так и HTTP-URL (адрес [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) метод

Загружает XML-документ из указанного потока.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, содержащий XML-документ для загрузки. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) метод

Загружает XML-документ из указанного TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader, используемый для подачи XML-данных в документ. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) метод

Загружает XML-документ из указанного [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) используется для подачи XML-данных в документ. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [XmlDocument](../)
* Класс [Stream](../../../system.io/stream/)
* Класс [TextReader](../../../system.io/textreader/)
* Класс [XmlReader](../../xmlreader/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)