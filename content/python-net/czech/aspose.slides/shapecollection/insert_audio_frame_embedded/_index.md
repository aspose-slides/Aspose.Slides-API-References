---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides pro Python přes .NET referenční příručku
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Vytvoří nový audio rámec s vloženým souborem WAV a vloží jej do kolekce tvarů na určeném indexu. Vložený audio soubor je přidán do kolekce Presentation.Audios.

### Vrací

Nově vytvořený [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | **io.RawIOBase** | An input stream containing WAV audio data to embed. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Vytvoří nový audio rámec a vloží jej do kolekce tvarů na určeném indexu pomocí existujícího audio objektu ze seznamu Presentation.Audios.

### Vrací

Nově vytvořený [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) | Instance [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) ze sbírky Presentation.Audios k vložení. |



### Viz také
* třída [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio)
* třída [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)