---
title: save method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Enregistre l'image dans un fichier.

```python
def save(self, filename):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| filename | **str** | Le chemin du fichier où l'image sera enregistrée. |

## save(self, filename, format) {#str-imageformat}
Enregistre l'image dans un fichier au format spécifié.

```python
def save(self, filename, format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| filename | **str** | Le chemin du fichier où l'image sera enregistrée. |
| format | [`ImageFormat`](/slides/python-net/fr/aspose.slides/imageformat) | Le format de l'image. |

## save(self, stream, format) {#iorawiobase-imageformat}
Enregistre l'image dans un flux au format spécifié.

```python
def save(self, stream, format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Le flux où l'image sera enregistrée. |
| format | [`ImageFormat`](/slides/python-net/fr/aspose.slides/imageformat) | Le format de l'image. |

## save(self, filename, format, quality) {#str-imageformat-int}
Enregistre l'image dans un fichier au format spécifié et avec la qualité spécifiée.

```python
def save(self, filename, format, quality):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| filename | **str** | Le chemin du fichier où l'image sera enregistrée. |
| format | [`ImageFormat`](/slides/python-net/fr/aspose.slides/imageformat) | Le format de l'image. |
| quality | **int** | La qualité de l'image enregistrée (0 à 100).  <br/><br/>            Ce paramètre n'affecte que l'enregistrement en [`ImageFormat.JPEG`](/slides/python-net/fr/aspose.slides/imageformat/JPEG) ; pour tous les autres formats, il est ignoré. |

## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Enregistre l'image dans un flux au format spécifié et avec la qualité spécifiée.

```python
def save(self, stream, format, quality):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Le flux où l'image sera enregistrée. |
| format | [`ImageFormat`](/slides/python-net/fr/aspose.slides/imageformat) | Le format de l'image. |
| quality | **int** | La qualité de l'image enregistrée (0 à 100).  <br/><br/>            Ce paramètre n'affecte que l'enregistrement en [`ImageFormat.JPEG`](/slides/python-net/fr/aspose.slides/imageformat/JPEG) ; pour tous les autres formats, il est ignoré. |

### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ImageFormat`](/slides/python-net/fr/aspose.slides/imageformat)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)