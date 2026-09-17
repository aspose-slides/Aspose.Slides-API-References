---
title: save method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML.


```python
def save(self, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/fr/aspose.slides.export.xaml/ixamloptions) | Les options de format XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié.


```python
def save(self, fname, format):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| fname | **str** | Chemin du fichier créé. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié.


```python
def save(self, stream, format):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux de sortie. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié avec des options supplémentaires.


```python
def save(self, fname, format, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| fname | **str** | Chemin du fichier créé. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |
| options | [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions) | Options de format supplémentaires. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires.


```python
def save(self, stream, format, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux de sortie. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |
| options | [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions) | Options de format supplémentaires. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Si vous essayez d’enregistrer un fichier chiffré dans <br/>            none Office 2007-2010 format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié.


```python
def save(self, fname, slides, format):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| fname | **str** | Chemin du fichier créé. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lorsque le paramètre stream ou slides est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Lorsque le paramètre slides contient des numéros de page incorrects. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié.


```python
def save(self, stream, slides, format):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux de sortie. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lorsque le paramètre stream ou slides est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Lorsque le paramètre slides contient des numéros de page incorrects. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié.


```python
def save(self, fname, slides, format, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| fname | **str** | Chemin du fichier créé. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |
| options | [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions) | Options de format supplémentaires. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lorsque le paramètre stream ou slides est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Lorsque le paramètre slides contient des numéros de page incorrects. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié.


```python
def save(self, stream, slides, format, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux de sortie. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) | Format des données exportées. |
| options | [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions) | Options de format supplémentaires. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lorsque le paramètre stream ou slides est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Lorsque le paramètre slides contient des numéros de page incorrects. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Voir aussi
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* classe [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions)
* classe [`IXamlOptions`](/slides/python-net/fr/aspose.slides.export.xaml/ixamloptions)
* énumération [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)