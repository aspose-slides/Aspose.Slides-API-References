---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Vytvoří nový audio rámeček s vloženým souborem WAV a vloží jej do kolekce tvarů na zadaném indexu. Vložený zvuk je přidán do kolekce Presentation.Audios.

### Returns

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
Vytvoří nový audio rámeček a vloží jej do kolekce tvarů na zadaném indexu pomocí existujícího audio objektu ze seznamu Presentation.Audios.

### Returns

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
| audio | [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) | An [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio) instance from the Presentation.Audios collection to embed. |



### Viz také
* třída [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio)
* třída [`IAudioFrame`](/slides/python-net/cs/aspose.slides/iaudioframe)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)