---
title: compress_image method
second_title: Référence de l'API Aspose.Slides for Python via .NET
description: 
type: docs
url: /fr/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Facultativement, il supprime également les zones recadrées.

### Returns
Retourne

Un **bool** indiquant si l'image a été compressée avec succès. Retourne **True** si l'image a été redimensionnée ou recadrée, sinon **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si true, la méthode supprimera les zones recadrées de l'image, réduisant potentiellement davantage sa taille. |
| resolution | [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression) | La résolution cible pour la compression, spécifiée comme une valeur de l'énumération [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression). |

### Remarks
Remarques

Cette méthode modifie la taille et la résolution de l'image de la même manière que la fonction « Picture Format -> Compress Pictures » de PowerPoint.

### Exceptions
Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque la résolution n'est pas une valeur valide. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Facultativement, il supprime également les zones recadrées.

### Returns
Retourne

Un **bool** indiquant si l'image a été compressée avec succès. Retourne **True** si l'image a été redimensionnée ou recadrée, sinon **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Si true, la méthode supprimera les zones recadrées de l'image, réduisant potentiellement davantage sa taille. |
| resolution | **float** | La résolution cible en DPI. Cette valeur doit être positive et détermine comment l'image sera redimensionnée. |

### Remarks
Remarques

Cette méthode modifie la taille et la résolution de l'image de la même manière que la fonction « Picture Format -> Compress Pictures » de PowerPoint.

### Exceptions
Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque la résolution n'est pas une valeur positive. |



### See Also
Voir aussi
* classe [`PictureFillFormat`](/slides/python-net/fr/aspose.slides/picturefillformat)
* énumération [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)