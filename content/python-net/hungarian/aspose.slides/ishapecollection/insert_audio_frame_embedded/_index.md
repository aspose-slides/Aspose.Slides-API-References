---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Új hangkeretet hoz létre beágyazott WAV fájlokkal, és beszúrja a shape gyűjteménybe a megadott indexnél. A beágyazott hangot a Presentation.Audios gyűjteményhez adják hozzá.

### Visszatérési érték

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az a nullától számított index, amelynél a hangkeretet be kell szúrni. |
| x | **float** | Az új hangkeret x koordinátája pontban. |
| y | **float** | Az új hangkeret y koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio_stream | **io.RawIOBase** | Beviteli adatfolyam, amely WAV hang adatot tartalmaz a beágyazáshoz. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Új hangkeretet hoz létre, és a shape gyűjteménybe szúrja be a megadott indexnél, a Presentation.Audios listából származó meglévő audio objektum használatával.

### Visszatérési érték

Az újonnan létrehozott [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az a nullától számított index, amelynél a hangkeretet be kell szúrni. |
| x | **float** | Az új hangkeret x koordinátája pontban. |
| y | **float** | Az új hangkeret y koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio | [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) | Egy [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből a beágyazáshoz. |



### Lásd még
* osztály [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio)
* osztály [`IAudioFrame`](/slides/python-net/hu/aspose.slides/iaudioframe)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)