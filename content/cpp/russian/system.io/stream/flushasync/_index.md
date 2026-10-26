---
title: FlushAsync()
second_title: Справочник API Aspose.Slides для C++
description: Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные быть записанными в нижележущее устройство, и отслеживает запросы отмены.
type: docs
weight: 118
url: /ru/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) метод


Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные быть записанными в нижележущее устройство, и отслеживает запросы отмены.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен, который отслеживает запросы отмены. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию сброса.

## Stream::FlushAsync() метод


Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные быть записанными в нижележущее устройство, и отслеживает запросы отмены.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Возвращаемое значение

Задача, представляющая асинхронную операцию сброса.

## См. также

* Typedef [TaskPtr](../../../system/taskptr/)
* Класс [CancellationToken](../../../system.threading/cancellationtoken/)
* Класс [Stream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)