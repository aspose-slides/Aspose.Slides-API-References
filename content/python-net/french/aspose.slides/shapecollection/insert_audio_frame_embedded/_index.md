---
title: insert_audio_frame_embedded method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios.

### Returns

Le [`IAudioFrame`](/slides/python-net/fr/aspose.slides/iaudioframe) nouvellement créé.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro à lequel insérer le cadre audio. |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio_stream | **io.RawIOBase** | Un flux d'entrée contenant des données audio WAV à intégrer. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la collection Presentation.Audios.

### Returns

Le [`IAudioFrame`](/slides/python-net/fr/aspose.slides/iaudioframe) nouvellement créé.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro à lequel insérer le cadre audio. |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio | [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio) | Une instance [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio) de la collection Presentation.Audios à intégrer. |



### Voir aussi
* classe [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio)
* classe [`IAudioFrame`](/slides/python-net/fr/aspose.slides/iaudioframe)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)