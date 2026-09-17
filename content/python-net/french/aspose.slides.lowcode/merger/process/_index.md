---
title: process method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | Un tableau contenant les noms de fichiers de présentation d'entrée. |
| output_file_name | **str** | Le nom du fichier de sortie de la présentation fusionnée résultante. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque les noms de fichiers d'entrée sont invalides ou que les formats ne correspondent pas. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | Un tableau contenant les noms de fichiers de présentation d'entrée. |
| output_stream | **io.RawIOBase** | Le flux de sortie. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque les noms de fichiers d'entrée sont invalides ou que les formats ne correspondent pas. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | Un tableau contenant les noms de fichiers de présentation d'entrée. |
| output_file_name | **str** | Le nom du fichier de sortie de la présentation fusionnée résultante. |
| options | [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions) | Les options supplémentaires qui définissent comment la présentation fusionnée est enregistrée. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque les noms de fichiers d'entrée sont invalides ou que les formats ne correspondent pas. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | Un tableau contenant les noms de fichiers de présentation d'entrée. |
| output_stream | **io.RawIOBase** | Le flux de sortie. |
| options | [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions) | Les options supplémentaires qui définissent comment la présentation fusionnée est enregistrée. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque les noms de fichiers d'entrée sont invalides ou que les formats ne correspondent pas. |

### Voir aussi
* classe [`ISaveOptions`](/slides/python-net/fr/aspose.slides.export/isaveoptions)
* classe [`Merger`](/slides/python-net/fr/aspose.slides.lowcode/merger)
* module [`aspose.slides.lowcode`](/slides/python-net/fr/aspose.slides.lowcode)
* bibliothèque [`Aspose.Slides`](/slides/python-net)