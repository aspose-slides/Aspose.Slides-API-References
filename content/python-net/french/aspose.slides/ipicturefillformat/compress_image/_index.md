---
title: compress_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées.

### Valeur de retour

Un **bool** indiquant si l'image a été compressée avec succès. Renvoie **True** si l'image a été redimensionnée ou recadrée, sinon **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si vrai, la méthode supprimera les zones recadrées de l'image, ce qui pourra réduire davantage sa taille. |
| resolution | [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression) | La résolution cible pour la compression, spécifiée comme une valeur de l'énumération [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression). |

### Remarques

Cette méthode modifie la taille et la résolution de l'image de façon similaire à la fonctionnalité "Picture Format -> Compress Pictures" de PowerPoint.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Provoquée lorsque la résolution n'est pas une valeur valide. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées.

### Valeur de retour

Un **bool** indiquant si l'image a été compressée avec succès. Renvoie **True** si l'image a été redimensionnée ou recadrée, sinon **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si vrai, la méthode supprimera les zones recadrées de l'image, ce qui pourra réduire davantage sa taille. |
| resolution | **float** | La résolution cible en DPI. Cette valeur doit être positive et définit comment l'image sera redimensionnée. |

### Remarques

Cette méthode modifie la taille et la résolution de l'image de façon similaire à la fonctionnalité "Picture Format -> Compress Pictures" de PowerPoint.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Provoquée lorsque la résolution n'est pas une valeur positive. |



### Voir aussi
* classe [`IPictureFillFormat`](/slides/python-net/fr/aspose.slides/ipicturefillformat)
* énumération [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)