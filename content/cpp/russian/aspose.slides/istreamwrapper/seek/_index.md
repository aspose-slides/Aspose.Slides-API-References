---
title: Seek()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает позицию в текущем потоке
type: docs
weight: 131
url: /ru/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) метод


Устанавливает позицию в текущем потоке

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно параметра origin типа **int64_t** |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | Значение типа [System::IO::SeekOrigin](../../../system.io/seekorigin/), указывающее точку отсчёта, используемую для получения новой позиции |

### Возвращаемое значение

Новая позиция в текущем потоке **int64_t**

## См. также

* Перечисление [SeekOrigin](../../../system.io/seekorigin/)
* Класс [IStreamWrapper](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)