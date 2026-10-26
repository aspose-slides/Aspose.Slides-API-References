---
title: add_audio_frame_embedded method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Létrehoz egy új audio keretet beágyazott WAV fájllal, és az alak gyűjtemény végéhez adja hozzá. A beágyazott audio a Presentation.Audios gyűjteményhez kerül hozzáadva.

### Visszatérési érték

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új audio keret x-koordinátája pontban. |
| y | **float** | Az új audio keret y-koordinátája pontban. |
| width | **float** | Az új audio keret szélessége pontban. |
| height | **float** | Az új audio keret magassága pontban. |
| audio_stream | **io.RawIOBase** | Egy bemeneti adatfolyam, amely WAV audio adatokat tartalmaz a beágyazáshoz. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Létrehoz egy új audio keretet, és az alak gyűjtemény végéhez adja hozzá egy meglévő audio objektum használatával a Presentation.Audios listáról.

### Visszatérési érték

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új audio keret x-koordinátája pontban. |
| y | **float** | Az új audio keret y-koordinátája pontban. |
| width | **float** | Az új audio keret szélessége pontban. |
| height | **float** | Az új audio keret magassága pontban. |
| audio | [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) | Egy [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) példány a Presentation.Audios kollekciójából. |



### Lásd még
* osztály [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio)
* osztály [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)