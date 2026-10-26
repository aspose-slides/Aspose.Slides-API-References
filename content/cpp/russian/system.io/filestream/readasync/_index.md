---
title: ReadAsync()
second_title: Справочник API Aspose.Slides для C++
description: Асинхронно считывает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы на отмену.
type: docs
weight: 196
url: /ru/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) метод

Асинхронно считывает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы на отмену.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты. |
| offset | **int32_t** | Позиция в **buffer**, начинающаяся с 0, с которой начинать запись. |
| count | **int32_t** | Количество байтов для чтения. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен, используемый для отслеживания запросов на отмену. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию чтения. Значение параметра TResult содержит общее количество байтов, прочитанных в буфер. Значение результата может быть меньше запрошенного количества байтов, если доступно меньше байтов, чем запрошено, или может быть 0 (ноль), если достигнут конец потока.

## См. также

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [CancellationToken](../../../system.threading/cancellationtoken/)
* Класс [FileStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)