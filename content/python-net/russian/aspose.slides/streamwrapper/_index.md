---
title: StreamWrapper class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/streamwrapper/
---
## StreamWrapper класс

Обёртка Aspose.IO.Stream для COM интерфейса.

Тип StreamWrapper раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`stream`](/slides/python-net/ru/aspose.slides/streamwrapper/stream/) | Получает поток.<br/>            Только чтение **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ru/aspose.slides/streamwrapper/can_read/) | Получает значение, указывающее, поддерживает ли текущий поток чтение.<br/>            Только чтение **bool**. |
| [`can_seek`](/slides/python-net/ru/aspose.slides/streamwrapper/can_seek/) | Получает значение, указывающее, поддерживает ли текущий поток поиск.<br/>            Только чтение **bool**. |
| [`can_write`](/slides/python-net/ru/aspose.slides/streamwrapper/can_write/) | Получает значение, указывающее, поддерживает ли текущий поток запись.<br/>            Только чтение **bool**. |
| [`length`](/slides/python-net/ru/aspose.slides/streamwrapper/length/) | Получает длину потока в байтах.<br/>            Только чтение **int**. |
| [`position`](/slides/python-net/ru/aspose.slides/streamwrapper/position/) | Получает или задаёт позицию в текущем потоке.<br/>            Только чтение **int**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`close(self)`](/slides/python-net/ru/aspose.slides/streamwrapper/close/#) | Закрывает текущий поток и освобождает все ресурсы. |
| [`flush(self)`](/slides/python-net/ru/aspose.slides/streamwrapper/flush/#) | Очищает все буферы этого потока и заставляет все буферизованные данные записаться в нижележущее устройство. |
| [`read(self, buffer, offset, count)`](/slides/python-net/ru/aspose.slides/streamwrapper/read/#bytes-int-int) | Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [`read_byte(self)`](/slides/python-net/ru/aspose.slides/streamwrapper/read_byte/#) | Читает один байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока. |
| [`seek(self, offset, origin)`](/slides/python-net/ru/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Устанавливает позицию в текущем потоке. |
| [`write(self, buffer, offset, count)`](/slides/python-net/ru/aspose.slides/streamwrapper/write/#bytes-int-int) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [`write_byte(self, value)`](/slides/python-net/ru/aspose.slides/streamwrapper/write_byte/#int) | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)