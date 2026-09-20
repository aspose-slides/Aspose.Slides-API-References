---
title: add_audio method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Přidá kopii zvukového souboru z jiné prezentace.

### Návratová hodnota
Přidaný zvuk.

```python
def add_audio(self, audio):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) | Zdrojový zvuk. |

## add_audio(self, stream) {#iorawiobase}
Vytvoří a přidá zvuk do prezentace ze streamu.

### Návratová hodnota
Přidaný zvuk.

```python
def add_audio(self, stream):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, ze kterého se přidá zvuk. |

## add_audio(self, audio_data) {#bytes}
Vytvoří a přidá zvuk do prezentace z pole bajtů.

### Návratová hodnota
Přidaný zvuk.

```python
def add_audio(self, audio_data):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| audio_data | **bytes** | Bajty zvuku. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Vytvoří a přidá zvuk do prezentace ze streamu.

### Návratová hodnota
Přidaný zvuk.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, ze kterého se přidá video zvuk. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior) | Chování, které bude aplikováno na stream. |

### Viz také
* třída [`AudioCollection`](/slides/python-net/cs/aspose.slides/audiocollection)
* třída [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio)
* výčtový typ [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)