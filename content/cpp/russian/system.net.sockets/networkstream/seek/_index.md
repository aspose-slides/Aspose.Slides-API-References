---
title: Seek()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 183
url: /ru/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) метод

Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, указанной **origin** |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Указывает позицию, от которой и направление, в сторону которого рассчитывается смещение |

### Возвращаемое значение

Новая позиция потока

## Смотрите также

* Перечисление [SeekOrigin](../../../system.io/seekorigin/)
* Класс [NetworkStream](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)