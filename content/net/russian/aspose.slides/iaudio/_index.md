---
title: IAudio
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет встроенный аудиофайл.
type: docs
weight: 4730
url: /ru/aspose.slides/iaudio/
---
## IAudio interface

Представляет встроенный аудиофайл.

```csharp
public interface IAudio
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BinaryData](../../aspose.slides/iaudio/binarydata) { get; } | Возвращает копию аудиоданных. В случае большого объема данных рассмотрите использование метода[`GetStream`](./getstream)для предотвращения ненужной загрузки аудио данных в memory или даже OutOfMemoryException. Только для чтенияByte[]. |
| [ContentType](../../aspose.slides/iaudio/contenttype) { get; } | Возвращает MIME-тип аудио, закодированный в[`BinaryData`](./binarydata). Только чтениеString. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetStream](../../aspose.slides/iaudio/getstream)() | Возвращает поток Stream для чтения. Используйте 'using' или закройте поток после использования. |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
