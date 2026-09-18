---
title: add_audio method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Dodaje kopię pliku audio z innej prezentacji.

### Zwraca

Dodane audio.



```python
def add_audio(self, audio):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) | Źródłowy audio. |


## add_audio(self, stream) {#iorawiobase}
Tworzy i dodaje audio do prezentacji ze strumienia.

### Zwraca

Dodane audio.



```python
def add_audio(self, stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, z którego dodać audio. |


## add_audio(self, audio_data) {#bytes}
Tworzy i dodaje audio do prezentacji z tablicy bajtów.

### Zwraca

Dodane audio.



```python
def add_audio(self, audio_data):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| audio_data | **bytes** | Bajty audio. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Tworzy i dodaje audio do prezentacji ze strumienia.

### Zwraca

Dodane audio.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, z którego dodać audio wideo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior) | Zachowanie, które zostanie zastosowane do strumienia. |



### Zobacz także
* klasa [`AudioCollection`](/slides/python-net/pl/aspose.slides/audiocollection)
* klasa [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio)
* enumeracja [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)