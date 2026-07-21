---
title: Seek()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 79
url: /ru/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) метод

Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | int | Смещение в байтах относительно позиции, указанной **origin** |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в котором рассчитывается смещение |

### Возвращаемое значение

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Класс [BinaryWriter](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)