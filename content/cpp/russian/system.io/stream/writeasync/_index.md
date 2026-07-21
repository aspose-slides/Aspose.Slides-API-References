---
title: WriteAsync()
second_title: Aspose.Slides для C++ справочник API
description: Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены.
type: docs
weight: 66
url: /ru/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) метод


Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи. |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | **int32_t** | Количество элементов в поддиапазоне для записи. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен для отслеживания запросов отмены. |

### Return Value

Задача, представляющая асинхронную операцию записи.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи. |
| offset | **int32_t** | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | **int32_t** | Количество элементов в поддиапазоне для записи. |

### Return Value

Задача, представляющая асинхронную операцию записи.

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [CancellationToken](../../../system.threading/cancellationtoken/)
* Класс [Stream](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)