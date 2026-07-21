---
title: XmlTextWriter()
second_title: Справка по API Aspose.Slides для C++
description: Создает экземпляр класса XmlTextWriter с использованием указанного потока и кодировки.
type: docs
weight: 183
url: /ru/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) конструктор


Создает экземпляр класса [XmlTextWriter](../) с использованием указанного потока и кодировки.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, в который вы хотите записать. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для генерации. Если кодировка **nullptr**, запись производится в поток как UTF-8 и атрибут кодировки опускается в **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) конструктор


Создает экземпляр класса [XmlTextWriter](../) с использованием указанного файла.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла для записи. Если файл существует, он усекается и перезаписывается новым содержимым. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для генерации. Если кодировка **nullptr**, файл записывается как UTF-8 и атрибут кодировки опускается в **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) конструктор


Создает экземпляр класса [XmlTextWriter](../) с использованием указанного TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter для записи. Предполагается, что TextWriter уже установлен с правильной кодировкой. |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [Encoding](../../../system.text/encoding/)
* Класс [XmlTextWriter](../)
* Класс [String](../../../system/string/)
* Класс [TextWriter](../../../system.io/textwriter/)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)