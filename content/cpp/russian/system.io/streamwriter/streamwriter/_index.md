---
title: StreamWriter()
second_title: Aspose.Slides для C++ справка по API
description: Создает экземпляр объекта StreamWriter, который записывает символы в указанный базовый поток, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта.
type: docs
weight: 1
url: /ru/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) конструктор


Создает экземпляр объекта [StreamWriter](../), который записывает символы в указанный базовый поток, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, в который записываются символы |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) конструктор


Создает экземпляр объекта [StreamWriter](../), который записывает символы в указанный базовый поток, используя указанную кодировку и буфер размером по умолчанию 1024 байта.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, в который записываются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которая будет использоваться |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) конструктор


Создает экземпляр объекта [StreamWriter](../), который записывает символы в указанный базовый поток, используя указанную кодировку и буфер указанного размера. Параметр указывает, следует ли закрывать базовый поток при освобождении объекта [StreamWriter](../).

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, в который записываются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которая будет использоваться |
| buffer_size | int | Минимальный размер буфера в байтах |
| leave_open | **bool** | Указывает, следует ли оставлять базовый поток открытым после того, как текущий объект [StreamWriter](../) будет освобожден |

## StreamWriter::StreamWriter(const String\&) конструктор


Создает экземпляр объекта [StreamWriter](../), который записывает символы в указанный файл, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, в который будут записываться символы |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) конструктор


Создает экземпляр объекта [StreamWriter](../), который записывает символы в указанный файл, используя указанную кодировку и буфер размером по умолчанию 1024 байта. Параметр задает, следует ли добавлять данные в конец файла или перезаписывать файл.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, в который будут записываться символы |
| append | **bool** | Указывает, следует ли добавлять данные в указанный файл (true) или перезаписать файл (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которая будет использоваться |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) конструктор


Создает экземпляр объекта [StreamWriter](../), который записывает символы в указанный файл, используя указанную кодировку и заданный размер буфера. Параметр задает, следует ли добавлять данные в файл или перезаписывать его.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, в который будут записываться символы |
| append | **bool** | Указывает, следует ли добавлять данные в указанный файл (true) или перезаписать файл (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которая будет использоваться |
| buffer_size | int | Размер буфера, который будет использоваться |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)