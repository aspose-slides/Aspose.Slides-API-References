---
title: add_audio method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Hozzáad egy másik bemutatóból származó hangfájl másolatát.

### Visszatér
Hozzáadott hang.

```python
def add_audio(self, audio):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) | Forrás hang. |

## add_audio(self, stream) {#iorawiobase}
Létrehozza és hozzáad egy hangot a bemutatóhoz adatfolyamból.

### Visszatér
Hozzáadott hang.

```python
def add_audio(self, stream):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Adatfolyam, amelyből a hangot hozzáadja. |

## add_audio(self, audio_data) {#bytes}
Létrehozza és hozzáad egy hangot a bemutatóhoz bájt tömbből.

### Visszatér
Hozzáadott hang.

```python
def add_audio(self, audio_data):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| audio_data | **bytes** | Hangbájtok. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Létrehozza és hozzáad egy hangot a bemutatóhoz adatfolyamból.

### Visszatér
Hozzáadott hang.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Adatfolyam, amelyből a videó hangot hozzáadja. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior) | A viselkedés, amely az adatfolyamra lesz alkalmazva. |

### Lásd még
* osztály [`AudioCollection`](/slides/python-net/hu/aspose.slides/audiocollection)
* osztály [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio)
* enumeráció [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)