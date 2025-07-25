---
title: AudioCollection
second_title: Aspose.Sildes for .NET API Reference
description: Represents a collection of embedded audio files.
type: docs
weight: 840
url: /aspose.slides/audiocollection/
---

## AudioCollection class

Represents a collection of embedded audio files.

```csharp
public class AudioCollection : DomObject<Presentation>, IAudioCollection
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/audiocollection/count) { get; } | Returns a number of audio files in the collection. Read-only Int32. |
| [IsSynchronized](../../aspose.slides/audiocollection/issynchronized) { get; } | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only Boolean. |
| [Item](../../aspose.slides/audiocollection/item) { get; } | Gets the element at the specified index. Read-only [`IAudio`](../iaudio). |
| [SyncRoot](../../aspose.slides/audiocollection/syncroot) { get; } | Returns a synchronization root. Read-only Object. |

## Methods

| Name | Description |
| --- | --- |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_1)(byte[]) | Creates and adds a audio to a presentation from byte array. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio)(IAudio) | Adds a copy of an audio file from an another presentation. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_2)(Stream) | Creates and adds a audio to a presentation from stream. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_3)(Stream, LoadingStreamBehavior) | Creates and adds a audio to a presentation from stream. |
| [CopyTo](../../aspose.slides/audiocollection/copyto)(Array, int) | Copies audios to specified array starting from specified index. |
| [GetEnumerator](../../aspose.slides/audiocollection/getenumerator)() | Returns an enumerator that iterates through the collection. |

### See Also

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [IAudioCollection](../iaudiocollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
