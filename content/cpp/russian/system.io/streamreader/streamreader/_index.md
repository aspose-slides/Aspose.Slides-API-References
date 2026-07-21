---
title: StreamReader()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт экземпляр объекта StreamReader, который читает символы из указанного базового потока, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта.
type: docs
weight: 1
url: /ru/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного базового потока, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, из которого читаются символы |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного базового потока, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта. Параметр определяет, должна ли быть включена проверка маркеров порядка байтов.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, из которого читаются символы |
| detectEncodingFromByteOrderMarks | **bool** | True, если нужно искать маркеры порядка байтов в начале потока, иначе - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного базового потока, используя заданную кодировку и буфер размером по умолчанию 1024 байта.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, из которого читаются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которую следует использовать |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного базового потока, используя заданную кодировку и буфер размером по умолчанию 1024 байта. Параметр определяет, должна ли быть включена проверка маркеров порядка байтов.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, из которого читаются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которую следует использовать |
| detectEncodingFromByteOrderMarks | **bool** | True, если нужно искать маркеры порядка байтов в начале потока, иначе - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного базового потока, используя заданную кодировку и буфер указанного размера. Параметр определяет, должна ли быть включена проверка маркеров порядка байтов.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Базовый поток, из которого читаются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которую следует использовать |
| detectEncodingFromByteOrderMarks | **bool** | True, если нужно искать маркеры порядка байтов в начале потока, иначе - false |
| bufferSize | int | Минимальный размер буфера в байтах |

## StreamReader::StreamReader(const System::String\&) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного файла, используя кодировку UTF-8 и буфер размером по умолчанию 4096 байт.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Путь к файлу, из которого читаются символы |

## StreamReader::StreamReader(const System::String\&, bool) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного файла, используя кодировку UTF-8 и буфер размером по умолчанию 4096 байт. Параметр определяет, должна ли быть включена проверка маркеров порядка байтов.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Путь к файлу, из которого читаются символы |
| detectEncodingFromByteOrderMarks | **bool** | True, если нужно искать маркеры порядка байтов в начале файла, иначе - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного файла, используя заданную кодировку и буфер размером по умолчанию 4096 байт.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Путь к файлу, из которого читаются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которую следует использовать |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного файла, используя заданную кодировку и буфер размером по умолчанию 4096 байт. Параметр определяет, должна ли быть включена проверка маркеров порядка байтов.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Путь к файлу, из которого читаются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которую следует использовать |
| detectEncodingFromByteOrderMarks | **bool** | True, если нужно искать маркеры порядка байтов в начале файла, иначе - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) конструктор

Создаёт экземпляр объекта [StreamReader](../), который читает символы из указанного файла, используя заданную кодировку и буфер указанного размера. Параметр определяет, должна ли быть включена проверка маркеров порядка байтов.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Путь к файлу, из которого читаются символы |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которую следует использовать |
| detectEncodingFromByteOrderMarks | **bool** | True, если нужно искать маркеры порядка байтов в начале файла, иначе - false |
| bufferSize | int | Минимальный размер буфера в байтах |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Класс [Stream](../../stream/)
* Класс [StreamReader](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)