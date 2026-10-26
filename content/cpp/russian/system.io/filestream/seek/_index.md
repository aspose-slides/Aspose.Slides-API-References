---
title: Seek()
second_title: Aspose.Slides для C++ справка API
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 209
url: /ru/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) метод

Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, указанной **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в сторону которого вычисляется смещение. |

### Возвращаемое значение

Новая позиция потока.

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Класс [FileStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)