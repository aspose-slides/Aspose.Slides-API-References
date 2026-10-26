---
title: MemoryStream()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса MemoryStream с начальной ёмкостью, равной 0.
type: docs
weight: 1
url: /ru/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() конструктор

Создает новый экземпляр класса [MemoryStream](../) с начальной ёмкостью, равной 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) конструктор

Создает новый экземпляр класса [MemoryStream](../), представляющего поток, основанный на буфере памяти указанного размера.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| capacity_ | int | Размер в байтах буфера памяти, связанного с потоком, представленным создаваемым объектом |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) конструктор

Создает новый экземпляр класса [MemoryStream](../), представляющего поток памяти, соединенный с указанным буфером памяти. Параметр определяет, является ли поток доступным для записи.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, используемый в качестве буфера памяти, на основе которого будет построен поток, представляемый создаваемым объектом |
| writable | **bool** | Указывает, должен ли поток быть доступным для записи |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) конструктор

Создает новый экземпляр класса [MemoryStream](../), представляющего поток памяти, соединенный с сегментом указанного буфера памяти, начинающимся с заданного индекса и включающим заданное количество элементов. Параметры определяют, может ли поток быть доступным для записи и может ли быть вызван метод GetBytes().

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, сегмент которого будет использоваться в качестве буфера памяти, на основе которого будет построен поток, представляемый создаваемым объектом |
| index | int | Нулевой индекс элемента в **content**, с которого начинается сегмент |
| count | int | Количество элементов **content**, включенных в сегмент |
| writable | **bool** | Указывает, должен ли поток быть доступным для записи |
| publiclyVisible | **bool** | Указывает, должен ли основной буфер памяти быть доступен вызывающему методу GetByte() |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [MemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)