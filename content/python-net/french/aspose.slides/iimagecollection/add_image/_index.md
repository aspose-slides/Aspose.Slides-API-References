---
title: add_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Ajoutez une image à une présentation.

### Renvoie
Image ajoutée.



```python
def add_image(self, image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/fr/aspose.slides/iimage) | Image à ajouter. |

### Remarques
Cette méthode convertit les métafichiers WMF/EMF en image PNG raster avant de les insérer dans une présentation.


## add_image(self, stream) {#iorawiobase}
Ajoutez une image à une présentation à partir d'un flux.

### Renvoie
Image ajoutée.



```python
def add_image(self, stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux à partir duquel ajouter l'image. |

### Remarques
Cette méthode peut ajouter des métafichiers WMF/EMF à une présentation sans les convertir en image PNG raster.


## add_image(self, buffer) {#bytes}
Ajoute une image à une présentation à partir du tampon spécifié.

### Renvoie
Image ajoutée.



```python
def add_image(self, buffer):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| buffer | **bytes** | Tampon. |


## add_image(self, image_source) {#ippimage}
Ajoute une copie d'une image d'une autre présentation.

### Renvoie
Image ajoutée.



```python
def add_image(self, image_source):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) | Image source. |


## add_image(self, svg_image) {#isvgimage}
Ajoutez une image à une présentation à partir d'un objet SVG.

### Renvoie
Image ajoutée.



```python
def add_image(self, svg_image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage) | Objet image SVG [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage) |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lancée lorsque le paramètre svgImage est None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crée et ajoute une image à une présentation à partir d'un flux.

### Renvoie
Added [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux à partir duquel ajouter le fichier image. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fr/aspose.slides/loadingstreambehavior) | Le comportement qui sera appliqué au flux. |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`IImageCollection`](/slides/python-net/fr/aspose.slides/iimagecollection)
* classe [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage)
* classe [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage)
* énumération [`LoadingStreamBehavior`](/slides/python-net/fr/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)