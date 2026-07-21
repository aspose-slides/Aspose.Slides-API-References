---
title: Seek()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 79
url: /ru/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) метод


Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, указанной **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в котором рассчитывается смещение |

### Возвращаемое значение

Новое положение потока

## См. также

* Перечисление [SeekOrigin](../../seekorigin/)
* Класс [BufferedStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)