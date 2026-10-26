---
title: Presentation constructor
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Ce constructeur crée une nouvelle présentation à partir de zéro.
            La présentation créée possède une diapositive vide.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Ce constructeur crée une nouvelle présentation à partir de zéro.
            La présentation créée possède une diapositive vide.

```python
def __init__(self, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/fr/aspose.slides/loadoptions) | Options de chargement supplémentaires. |

## __init__(self, stream) {#iorawiobase}
Ce constructeur est le mécanisme principal pour lire une présentation existante.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux d'entrée. |

## __init__(self, file) {#str}
Ce constructeur obtient un chemin de fichier source à partir duquel
             le contenu de la présentation est lu.

```python
def __init__(self, file):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file | **str** | Fichier d'entrée. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque le fichier d'entrée a une longueur nulle |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Ce constructeur est le mécanisme principal pour lire une présentation existante.

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux d'entrée. |
| load_options | [`LoadOptions`](/slides/python-net/fr/aspose.slides/loadoptions) | Options de chargement supplémentaires. |

## __init__(self, file, load_options) {#str-loadoptions}
Ce constructeur obtient un chemin de fichier source à partir duquel
            le contenu de la présentation est lu.

```python
def __init__(self, file, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file | **str** | Fichier d'entrée. |
| load_options | [`LoadOptions`](/slides/python-net/fr/aspose.slides/loadoptions) | Options de chargement supplémentaires. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque le fichier d'entrée a une longueur nulle |

### See Also
* classe [`LoadOptions`](/slides/python-net/fr/aspose.slides/loadoptions)
* classe [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)