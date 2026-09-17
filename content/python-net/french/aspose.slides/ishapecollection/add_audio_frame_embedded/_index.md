---
title: add_audio_frame_embedded method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection Presentation.Audios.

### Retour

The newly created [`IAudioFrame`](/slides/python-net/fr/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio_stream | **io.RawIOBase** | Un flux d'entrée contenant des données audio WAV à intégrer. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios.

### Retour

The newly created [`IAudioFrame`](/slides/python-net/fr/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio | [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio) | Une instance [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio) de la collection Presentation.Audios. |



### Voir aussi
* classe [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio)
* classe [`IAudioFrame`](/slides/python-net/fr/aspose.slides/iaudioframe)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)