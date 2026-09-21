---
title: add_audio method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Voegt een kopie van een audiobestand toe vanuit een andere presentatie.

### Returns
Toegevoegde audio.

```python
def add_audio(self, audio):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio) | Bron-audio. |

## add_audio(self, stream) {#iorawiobase}
Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream.

### Returns
Toegevoegde audio.

```python
def add_audio(self, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om audio toe te voegen. |

## add_audio(self, audio_data) {#bytes}
Maakt een audio aan en voegt deze toe aan een presentatie vanuit een byte-array.

### Returns
Toegevoegde audio.

```python
def add_audio(self, audio_data):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| audio_data | **bytes** | Audio-bytes. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Maakt een audio aan en voegt deze toe aan een presentatie vanuit een stream.

### Returns
Toegevoegde audio.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om video-audio toe te voegen. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior) | Het gedrag dat op de stream zal worden toegepast. |

### See Also
* klasse [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio)
* klasse [`IAudioCollection`](/slides/python-net/nl/aspose.slides/iaudiocollection)
* enumeratie [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)