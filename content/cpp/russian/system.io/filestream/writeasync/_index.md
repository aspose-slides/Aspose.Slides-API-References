---
title: WriteAsync()
second_title: Aspose.Slides для C++ справка API
description: Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены.
type: docs
weight: 261
url: /ru/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) метод

Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи. |
| offset | **int32_t** | Индекс начала поддиапазона в **buffer** (нумерация с нуля). |
| count | **int32_t** | Количество элементов в поддиапазоне для записи. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен, используемый для отслеживания запросов отмены. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию записи.

## Смотрите также

* Тип [TaskPtr](../../../system/taskptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [CancellationToken](../../../system.threading/cancellationtoken/)
* Класс [FileStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)