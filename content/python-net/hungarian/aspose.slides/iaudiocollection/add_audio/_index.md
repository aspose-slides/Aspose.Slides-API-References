---
title: add_audio method
second_title: Aspose.Slides a Python számára a .NET API hivatkozásával
description: 
type: docs
url: /hu/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Hozzáad egy másik bemutatóból származó audio fájl másolatát.

### Returns
Hozzáadott audio.



```python
def add_audio(self, audio):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio) | Forrás audio. |


## add_audio(self, stream) {#iorawiobase}
Létrehoz és hozzáad egy audio-t a bemutatóhoz egy adatfolyamból.

### Returns
Hozzáadott audio.



```python
def add_audio(self, stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az audio hozzáadásához használt adatfolyam. |


## add_audio(self, audio_data) {#bytes}
Létrehoz és hozzáad egy audio-t a bemutatóhoz egy bájt tömbből.

### Returns
Hozzáadott audio.



```python
def add_audio(self, audio_data):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| audio_data | **bytes** | Audio bájtok. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Létrehoz és hozzáad egy audio-t a bemutatóhoz egy adatfolyamból.

### Returns
Hozzáadott audio.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az video audio hozzáadásához használt adatfolyam. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior) | A stream-re alkalmazandó viselkedés. |



### See Also
* osztály [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio)
* osztály [`IAudioCollection`](/slides/python-net/hu/aspose.slides/iaudiocollection)
* enumeráció [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)