---
title: Seek()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 79
url: /ru/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) метод

Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, указанной параметром **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в котором рассчитывается смещение |

### Возвращаемое значение

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)