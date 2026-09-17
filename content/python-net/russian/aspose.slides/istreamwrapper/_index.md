---
title: IStreamWrapper class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/istreamwrapper/
---
## IStreamWrapper класс

Aspose.IO.Stream оболочка для COM-интерфейса.

Тип IStreamWrapper раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`stream`](/slides/python-net/ru/aspose.slides/istreamwrapper/stream/) | Получает поток.<br/>            Только для чтения **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ru/aspose.slides/istreamwrapper/can_read/) | Получает значение, указывающее, поддерживает ли текущий поток чтение.<br/>            Только для чтения **bool**. |
| [`can_seek`](/slides/python-net/ru/aspose.slides/istreamwrapper/can_seek/) | Получает значение, указывающее, поддерживает ли текущий поток поиск.<br/>            Только для чтения **bool**. |
| [`can_write`](/slides/python-net/ru/aspose.slides/istreamwrapper/can_write/) | Получает значение, указывающее, поддерживает ли текущий поток запись.<br/>            Только для чтения **bool**. |
| [`length`](/slides/python-net/ru/aspose.slides/istreamwrapper/length/) | Получает длину в байтах потока.<br/>            Только для чтения **int**. |
| [`position`](/slides/python-net/ru/aspose.slides/istreamwrapper/position/) | Получает позицию в текущем потоке.<br/>            Только для чтения **int**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`close(self)`](/slides/python-net/ru/aspose.slides/istreamwrapper/close/#) | Закрывает текущий поток и освобождает любые ресурсы. |
| [`flush(self)`](/slides/python-net/ru/aspose.slides/istreamwrapper/flush/#) | Очищает все буферы этого потока и заставляет любые буферизованные данные быть записанными в базовое устройство. |
| [`read(self, buffer, offset, count)`](/slides/python-net/ru/aspose.slides/istreamwrapper/read/#bytes-int-int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [`read_byte(self)`](/slides/python-net/ru/aspose.slides/istreamwrapper/read_byte/#) | Считывает байт из потока и перемещает позицию в потоке на один байт, или возвращает -1, если достигнут конец потока. |
| [`seek(self, offset, origin)`](/slides/python-net/ru/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Устанавливает позицию в текущем потоке |
| [`write(self, buffer, offset, count)`](/slides/python-net/ru/aspose.slides/istreamwrapper/write/#bytes-int-int) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [`write_byte(self, value)`](/slides/python-net/ru/aspose.slides/istreamwrapper/write_byte/#int) | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)