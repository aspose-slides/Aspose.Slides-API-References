---
title: to_png method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Convertit la présentation d'entrée en un ensemble d'images au format PNG.  
            Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", 
            le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Convertit la présentation d'entrée en un ensemble d'images au format PNG.  
            Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", 
            le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | The input presentation |
| output_file_name | **str** | The output file name. |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | The size of each generated image. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Convertit la présentation d'entrée en un ensemble d'images au format PNG.  
            Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", 
            le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |
| scale | **float** | The scaling factor applied to the output images relative to the original slide size. |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | The rendering options. |

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