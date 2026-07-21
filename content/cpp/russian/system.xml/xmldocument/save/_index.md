---
title: Save()
second_title: Справочник API Aspose.Slides для C++
description: Сохраняет XML-документ в указанный файл. Если указанный файл существует, этот метод перезаписывает его.
type: docs
weight: 534
url: /ru/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) метод


Сохраняет XML-документ в указанный файл. Если указанный файл существует, этот метод перезаписывает его.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Расположение файла, в котором вы хотите сохранить документ. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) метод


Сохраняет XML-документ в указанный поток.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, в который вы хотите сохранить данные. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) метод


Сохраняет XML-документ в указанный TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter, в который вы хотите сохранить данные. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) метод


Сохраняет XML-документ в указанный [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | [XmlWriter](../../xmlwriter/), в который вы хотите сохранить данные. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)