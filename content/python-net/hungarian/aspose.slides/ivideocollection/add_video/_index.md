---
title: add_video method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Egy videófájlt másolatként ad hozzá egy másik prezentációból.

### Visszatérési érték

Hozzáadott videó.

```python
def add_video(self, video):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo) | Forrás videó. |

## add_video(self, video_data) {#bytes}
Létrehozza és hozzáadja a videót egy prezentációhoz bájt tömbből.

### Visszatérési érték

Hozzáadott videó.

```python
def add_video(self, video_data):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| video_data | **bytes** | Videó bájtok. |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Létrehozza és hozzáadja a videót egy prezentációhoz adatfolyamról.

### Visszatérési érték

Hozzáadott [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo).

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az adatfolyam, amelyből a videófájlt hozzáadja. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior) | A viselkedés, amelyet az adatfolyamra alkalmaznak. |

### Lásd még
* osztály [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo)
* osztály [`IVideoCollection`](/slides/python-net/hu/aspose.slides/ivideocollection)
* enumeráció [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)