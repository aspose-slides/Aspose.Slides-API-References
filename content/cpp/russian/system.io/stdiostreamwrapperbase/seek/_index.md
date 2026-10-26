---
title: Seek()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 40
url: /ru/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) метод


Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Байтовое смещение относительно позиции, указанной **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Указывает позицию, от которой и направление, в котором вычисляется смещение |

### Возвращаемое значение

Новое положение потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Класс [STDIOStreamWrapperBase](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)