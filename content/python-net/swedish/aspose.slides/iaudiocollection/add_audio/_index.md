---
title: add_audio method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Lägger till en kopia av en ljudfil från en annan presentation.

### Returnerar

Added audio.

```python
def add_audio(self, audio):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio) | Källljud. |

## add_audio(self, stream) {#iorawiobase}
Skapar och lägger till ett ljud i en presentation från en ström.

### Returnerar

Added audio.

```python
def add_audio(self, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ström att lägga till ljud från. |

## add_audio(self, audio_data) {#bytes}
Skapar och lägger till ett ljud i en presentation från en byte-array.

### Returnerar

Added audio.

```python
def add_audio(self, audio_data):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| audio_data | **bytes** | Ljuddata. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Skapar och lägger till ett ljud i en presentation från en ström.

### Returnerar

Added audio.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ström att lägga till video-ljud från. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior) | Beteendet som kommer att tillämpas på strömmen. |

### Se även
* klass [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio)
* klass [`IAudioCollection`](/slides/python-net/sv/aspose.slides/iaudiocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)