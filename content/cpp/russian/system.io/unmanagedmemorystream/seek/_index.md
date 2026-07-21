---
title: Seek()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 157
url: /ru/system.io/unmanagedmemorystream/seek/
---
## UnmanagedMemoryStream::Seek(int64_t, SeekOrigin) метод

Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::UnmanagedMemoryStream::Seek(int64_t offset, SeekOrigin loc) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, указанной **origin** |
| loc | [SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в котором вычисляется смещение |

### Возвращаемое значение

Новая позиция потока

## См. также

* Перечисление [SeekOrigin](../../seekorigin/)
* Класс [UnmanagedMemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)