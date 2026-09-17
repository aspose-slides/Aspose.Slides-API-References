---
title: add_audio method
second_title: Aspose.Slides pour Python via .NET – Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Ajoute une copie d'un fichier audio provenant d'une autre présentation.

### Retour

Audio ajouté.



```python
def add_audio(self, audio):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio) | Audio source. |


## add_audio(self, stream) {#iorawiobase}
Crée et ajoute un audio à une présentation depuis un flux.

### Retour

Audio ajouté.



```python
def add_audio(self, stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux à partir duquel ajouter l'audio. |


## add_audio(self, audio_data) {#bytes}
Crée et ajoute un audio à une présentation à partir d'un tableau d'octets.

### Retour

Audio ajouté.



```python
def add_audio(self, audio_data):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| audio_data | **bytes** | Octets d'audio. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crée et ajoute un audio à une présentation depuis un flux.

### Retour

Audio ajouté.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux à partir duquel ajouter l'audio vidéo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fr/aspose.slides/loadingstreambehavior) | Le comportement qui sera appliqué au flux. |


### Voir aussi
* classe [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio)
* classe [`IAudioCollection`](/slides/python-net/fr/aspose.slides/iaudiocollection)
* énumération [`LoadingStreamBehavior`](/slides/python-net/fr/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)