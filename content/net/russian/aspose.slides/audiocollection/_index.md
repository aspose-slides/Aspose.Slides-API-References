---
title: AudioCollection
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет коллекцию встроенных аудиофайлов.
type: docs
weight: 780
url: /ru/aspose.slides/audiocollection/
---

## Класс AudioCollection

Представляет коллекцию встроенных аудиофайлов.

```csharp
public class AudioCollection : DomObject<Presentation>, IAudioCollection
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/audiocollection/count) { get; } | Возвращает количество аудиофайлов в коллекции. Только для чтения Int32. |
| [IsSynchronized](../../aspose.slides/audiocollection/issynchronized) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (безопасно для потоков). Только для чтения Boolean. |
| [Item](../../aspose.slides/audiocollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`IAudio`](../iaudio). |
| [SyncRoot](../../aspose.slides/audiocollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтения Object. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_1)(byte[]) | Создает и добавляет аудио в презентацию из массива байтов. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio)(IAudio) | Добавляет копию аудиофайла из другой презентации. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_2)(Stream) | Создает и добавляет аудио в презентацию из потока. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_3)(Stream, LoadingStreamBehavior) | Создает и добавляет аудио в презентацию из потока. |
| [CopyTo](../../aspose.slides/audiocollection/copyto)(Array, int) | Копирует аудиофайлы в указанный массив, начиная с указанного индекса. |
| [GetEnumerator](../../aspose.slides/audiocollection/getenumerator)() | Возвращает перечислитель, который проходит по коллекции. |

### См. также

* класс [DomObject&lt;TParent&gt;](../domobject-1)
* класс [Presentation](../presentation)
* интерфейс [IAudioCollection](../iaudiocollection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->