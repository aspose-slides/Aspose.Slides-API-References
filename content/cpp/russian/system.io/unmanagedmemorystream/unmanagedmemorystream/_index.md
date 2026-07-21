---
title: UnmanagedMemoryStream()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр UnmanagedMemoryStream.
type: docs
weight: 118
url: /ru/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) конструктор

Создаёт новый экземпляр [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pointer | **uint8_t** * | Указатель на неуправляемый буфер |
| length | **int64_t** | Размер неуправляемого буфера в байтах |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) конструктор

Создаёт новый экземпляр [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pointer | **uint8_t** * | Указатель на неуправляемый буфер |
| length | **int64_t** | Размер неуправляемого буфера в байтах |
| capacity | **int64_t** | Общий объём памяти, выделенный для потока |
| access | [FileAccess](../../fileaccess/) | Указывает, должен ли поток быть только для чтения, только для записи или оба |

## Смотрите также

* Enum [FileAccess](../../fileaccess/)
* Класс [UnmanagedMemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)