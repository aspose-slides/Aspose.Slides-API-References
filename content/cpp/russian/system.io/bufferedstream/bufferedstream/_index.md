---
title: BufferedStream()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект BufferedStream, который оборачивает указанный поток и использует буфер длиной 4096 байт.
type: docs
weight: 1
url: /ru/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) конструктор


Создаёт объект [BufferedStream](../), который оборачивает указанный поток и использует буфер длиной 4096 байт.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Основной объект [Stream](../../stream/) |
|  |  |  |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) конструктор


Создаёт объект [BufferedStream](../), который оборачивает указанный поток и использует буфер указанного размера.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Основной объект [Stream](../../stream/) |
| bufferSize | int | Размер буфера в байтах |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../stream/)
* Класс [BufferedStream](../)
* Пространство имен [System::IO](../../)
* Library [Aspose.Slides](../../../)