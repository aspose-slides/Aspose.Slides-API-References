---
title: add_audio_frame_embedded method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av shape-samlingen. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

### Returnerar

Det nyss skapade [`IAudioFrame`](/slides/python-net/sv/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio_stream | **io.RawIOBase** | En inmatningsström som innehåller WAV-ljuddata att bädda in. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Skapar en ny ljudram och lägger till den i slutet av shape-samlingen med ett befintligt ljudobjekt från Presentation.Audios-listan.

### Returnerar

Den nyss skapade [`IAudioFrame`](/slides/python-net/sv/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio | [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio) | En [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio)-instans från Presentation.Audios-samlingen. |


### Se även
* klass [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio)
* klass [`IAudioFrame`](/slides/python-net/sv/aspose.slides/iaudioframe)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)