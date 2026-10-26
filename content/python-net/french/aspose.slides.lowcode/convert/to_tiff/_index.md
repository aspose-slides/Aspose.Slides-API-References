---
title: to_tiff method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Convertit la présentation d'entrée en un ensemble d'images au format TIFF.  
            Si le nom du fichier de sortie est donné comme "myPath/myFilename.tiff", 
            le résultat sera enregistré sous forme d'un ensemble de "myPath/myFilename_N.tiff" fichiers, où N est le numéro d'une diapositive.


```python
@staticmethod
def to_tiff(pres, output_file_name):
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


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Convertit la présentation d'entrée au format TIFF avec des options personnalisées.
            Si le nom du fichier de sortie est donné comme "myPath/myFilename.tiff" et `multipage` est `false`, 
            le résultat sera enregistré sous forme d'un ensemble de "myPath/myFilename_N.tiff" fichiers, où N est le numéro d'une diapositive.
            Sinon, si `multipage` est `true`, le résultat sera un document multi-pages "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | La présentation d'entrée. |
| output_file_name | **str** | Le nom du fichier de sortie. |
| options | [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions) | Les options d'enregistrement TIFF. |
| multipage | **bool** | Spécifie si le document TIFF généré doit être multi-pages. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Voir aussi
* classe [`Convert`](/slides/python-net/fr/aspose.slides.lowcode/convert)
* classe [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions)
* classe [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/fr/aspose.slides.lowcode)
* bibliothèque [`Aspose.Slides`](/slides/python-net)