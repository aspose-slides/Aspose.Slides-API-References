---
title: to_jpeg method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Convertit la présentation d'entrée en un ensemble d'images au format JPEG.  
            Si le nom du fichier de sortie est donné comme "myPath/myFilename.jpeg", 
            le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | La présentation d'entrée. |
| output_file_name | **str** | Le nom du fichier de sortie. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Convertit la présentation d'entrée en un ensemble d'images au format JPEG.  
            Si le nom du fichier de sortie est donné comme "myPath/myFilename.jpeg", 
            le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | La présentation d'entrée |
| output_file_name | **str** | Le nom du fichier de sortie. |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | La taille de chaque image générée. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Convertit la présentation d'entrée en un ensemble d'images au format JPEG.  
            Si le nom du fichier de sortie est donné comme "myPath/myFilename.jpeg", 
            le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | La présentation d'entrée. |
| output_file_name | **str** | Le nom du fichier de sortie. |
| scale | **float** | Le facteur d'échelle appliqué aux images de sortie par rapport à la taille originale de la diapositive. |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Les options de rendu. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


### Voir aussi
* classe [`Convert`](/slides/python-net/fr/aspose.slides.lowcode/convert)
* classe [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* classe [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* classe [`Size`](/slides/python-net/fr/aspose.slides/size)
* module [`aspose.slides.lowcode`](/slides/python-net/fr/aspose.slides.lowcode)
* bibliothèque [`Aspose.Slides`](/slides/python-net)