---
title: add_video method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Ajoute une copie d’un fichier vidéo d’une autre présentation.

### Valeur de retour

Vidéo ajoutée.



```python
def add_video(self, video):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/fr/aspose.slides/ivideo) | Vidéo source. |


## add_video(self, video_data) {#bytes}
Crée et ajoute une vidéo à une présentation à partir d’un tableau d’octets.

### Valeur de retour

Vidéo ajoutée.



```python
def add_video(self, video_data):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| video_data | **bytes** | Octets vidéo. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crée et ajoute une vidéo à une présentation à partir d’un flux.

### Valeur de retour

Ajouté [`IVideo`](/slides/python-net/fr/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux d’où ajouter le fichier vidéo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fr/aspose.slides/loadingstreambehavior) | Le comportement qui sera appliqué au flux. |



### Voir aussi
* classe [`IVideo`](/slides/python-net/fr/aspose.slides/ivideo)
* classe [`IVideoCollection`](/slides/python-net/fr/aspose.slides/ivideocollection)
* énumération [`LoadingStreamBehavior`](/slides/python-net/fr/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)