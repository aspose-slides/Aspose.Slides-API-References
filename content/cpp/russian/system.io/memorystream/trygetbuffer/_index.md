---
title: TryGetBuffer()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает массив беззнаковых байтов, из которого был создан этот поток.
type: docs
weight: 170
url: /ru/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) метод

Возвращает массив беззнаковых байтов, из которого был создан этот поток.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | массив байтов - параметр вывода. Когда этот метод возвращает true, сегмент массива байтов, из которого был создан этот поток; когда метод возвращает false, этот параметр устанавливается в значение по умолчанию. |

### Возвращаемое значение

True, если преобразование удалось.

## См. также

* Класс [ArraySegment](../../../system/arraysegment/)
* Класс [MemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)