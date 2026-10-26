---
title: add_audio_frame_embedded method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Létrehoz egy új audio keretet egy beágyazott WAV fájllal, és hozzáadja a shape gyűjtemény végéhez.
            A beágyazott audió a Presentation.Audios gyűjteményhez kerül hozzáadásra.

### Visszatér

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új audio keret x-koordinátája pontokban. |
| y | **float** | Az új audio keret y-koordinátája pontokban. |
| width | **float** | Az új audio keret szélessége pontokban. |
| height | **float** | Az új audio keret magassága pontokban. |
| audio_stream | **io.RawIOBase** | Egy bemeneti adatfolyam, amely WAV audio adatot tartalmaz a beágyazáshoz. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Létrehoz egy új audio keretet, és hozzáadja a shape gyűjtemény végéhez egy
            meglévő audio objektum használatával a Presentation.Audios listából.

### Visszatér

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új audio keret x-koordinátája pontokban. |
| y | **float** | Az új audio keret y-koordinátája pontokban. |
| width | **float** | Az új audio keret szélessége pontokban. |
| height | **float** | Az új audio keret magassága pontokban. |
| audio | [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) | Egy [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből. |



### Lásd még
* osztály [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio)
* osztály [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)