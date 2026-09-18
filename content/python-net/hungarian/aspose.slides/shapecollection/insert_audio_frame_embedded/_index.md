---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Új hangkeretet hoz létre beágyazott WAV fájllal, és a megadott indexnél beilleszti a shape gyűjteménybe. A beágyazott hangot a Presentation.Audios gyűjteményhez adja hozzá.

### Visszatérési érték

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullánál kezdődő index, amelyen a hangkeretet be kell illeszteni. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio_stream | **io.RawIOBase** | WAV audio adatokat tartalmazó bemeneti folyam a beágyazáshoz. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Új hangkeretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti be, egy a Presentation.Audios listában már létező audioobjektum használatával.

### Visszatérési érték

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullánál kezdődő index, amelyen a hangkeretet be kell illeszteni. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio | [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) | A Presentation.Audios gyűjteményből származó [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) példány a beágyazáshoz. |



### Lásd még
* osztály [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio)
* osztály [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)