---
title: add_audio_frame_embedded method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený zvuk je přidán do kolekce Presentation.Audios.

### Návratová hodnota

The newly created [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového audio rámce v bodech. |
| y | **float** | Y-souřadnice nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| audio_stream | **io.RawIOBase** | Vstupní proud obsahující data WAV audio k vložení. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios.

### Návratová hodnota

The newly created [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového audio rámce v bodech. |
| y | **float** | Y-souřadnice nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| audio | [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) | Instance [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) ze sbírky Presentation.Audios. |



### Viz také
* třída [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio)
* třída [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)