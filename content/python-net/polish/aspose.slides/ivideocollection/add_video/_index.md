---
title: add_video method
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Dodaje kopię pliku wideo z innej prezentacji.

### Zwraca
Dodane wideo.

```python
def add_video(self, video):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo) | Wideo źródłowe. |

## add_video(self, video_data) {#bytes}
Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

### Zwraca
Dodane wideo.

```python
def add_video(self, video_data):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| video_data | **bytes** | Bajty wideo. |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Tworzy i dodaje wideo do prezentacji ze strumienia.

### Zwraca
Dodane [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo).

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, z którego ma zostać dodany plik wideo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior) | Zachowanie, które zostanie zastosowane do strumienia. |

### Zobacz także
* klasa [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo)
* klasa [`IVideoCollection`](/slides/python-net/pl/aspose.slides/ivideocollection)
* enumeracja [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)