---
title: Seek()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 105
url: /ru/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) метод


Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, заданной **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в котором вычисляется смещение |

### Возвращаемое значение

Новая позиция потока

## См. также

* Перечисление [SeekOrigin](../../seekorigin/)
* Класс [MemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)