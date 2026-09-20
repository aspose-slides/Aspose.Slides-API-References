---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i shape-samlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

### Returnerar

Den nyss skapade [`IAudioFrame`](/slides/python-net/sv/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio_stream | **io.RawIOBase** | En inmatningsström som innehåller WAV-ljuddata att bädda in. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Skapar en ny ljudram och infogar den i shape-samlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan.

### Returnerar

Den nyss skapade [`IAudioFrame`](/slides/python-net/sv/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| audio | [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio) | En [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio)-instans från Presentation.Audios-samlingen som ska bäddas in. |



### Se också
* klass [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio)
* klass [`IAudioFrame`](/slides/python-net/sv/aspose.slides/iaudioframe)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)