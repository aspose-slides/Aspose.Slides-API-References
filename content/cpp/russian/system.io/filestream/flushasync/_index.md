---
title: FlushAsync()
second_title: Справочник API Aspose.Slides для C++
description: Асинхронно очищает все буферы этого потока, заставляет любые буферизованные данные быть записанными в базовое устройство и отслеживает запросы на отмену.
type: docs
weight: 157
url: /ru/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) метод


Асинхронно очищает все буферы этого потока, заставляет любые буферизованные данные быть записанными в базовое устройство и отслеживает запросы на отмену.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен, который отслеживает запросы на отмену. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию очистки.

## См. также

* Тип [TaskPtr](../../../system/taskptr/)
* Класс [CancellationToken](../../../system.threading/cancellationtoken/)
* Класс [FileStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)