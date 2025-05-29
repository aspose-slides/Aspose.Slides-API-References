---
title: IStreamWrapper
second_title: Aspose.Sildes для .NET API Reference
description: Обертка Aspose.IO.Stream для COM интерфейса.
type: docs
weight: 6910
url: /ru/aspose.slides/istreamwrapper/
---

## Интерфейс IStreamWrapper

Обертка Aspose.IO.Stream для COM интерфейса.

```csharp
public interface IStreamWrapper : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIDisposable](../../aspose.slides/istreamwrapper/asidisposable) { get; } | Позволяет получить базовый интерфейс IDisposable. Только для чтения IDisposable. |
| [CanRead](../../aspose.slides/istreamwrapper/canread) { get; } | Получает значение, указывающее, поддерживает ли текущий поток чтение. Только для чтения Boolean. |
| [CanSeek](../../aspose.slides/istreamwrapper/canseek) { get; } | Получает значение, указывающее, поддерживает ли текущий поток поиск. Только для чтения Boolean. |
| [CanWrite](../../aspose.slides/istreamwrapper/canwrite) { get; } | Получает значение, указывающее, поддерживает ли текущий поток запись. Только для чтения Boolean. |
| [Length](../../aspose.slides/istreamwrapper/length) { get; } | Получает длину потока в байтах. Только для чтения Int64. |
| [Position](../../aspose.slides/istreamwrapper/position) { get; } | Получает позицию в текущем потоке. Только для чтения Int64. |
| [Stream](../../aspose.slides/istreamwrapper/stream) { get; } | Получает поток. Только для чтения Stream. |

## Методы

| Имя | Описание |
| --- | --- |
| [Close](../../aspose.slides/istreamwrapper/close)() | Закрывает текущий поток и освобождает все ресурсы. |
| [Flush](../../aspose.slides/istreamwrapper/flush)() | Очищает все буферы для этого потока и вызывает запись любых буферизированных данных на подлежащий устройство. |
| [Read](../../aspose.slides/istreamwrapper/read)(byte[], int, int) | Читает последовательность байтов из текущего потока и передвигает позицию в потоке на количество прочитанных байтов. |
| [ReadByte](../../aspose.slides/istreamwrapper/readbyte)() | Читает байт из потока и продвигает позицию в потоке на один байт или возвращает -1, если достигнут конец потока. |
| [Seek](../../aspose.slides/istreamwrapper/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке |
| [Write](../../aspose.slides/istreamwrapper/write)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| [WriteByte](../../aspose.slides/istreamwrapper/writebyte)(byte) | Записывает байт в текущую позицию в потоке и продвигает позицию в потоке на один байт. |

### См. также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->