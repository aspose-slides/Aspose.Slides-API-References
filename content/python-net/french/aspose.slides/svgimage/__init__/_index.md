---
title: SvgImage constructor
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/svgimage/__init__/
weight: 10
---
## __init__(self, data) {#bytes}
Crée un nouvel objet SvgImage.

```python
def __init__(self, data):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| data | **bytes** | Données Svg. |

## __init__(self, svg_content) {#str}
Crée un nouvel objet SvgImage.

```python
def __init__(self, svg_content):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| svg_content | **str** | Contenu Svg. |

## __init__(self, stream) {#iorawiobase}
Crée un nouvel objet SvgImage.

```python
def __init__(self, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux Svg. |

## __init__(self, data, external_res_resolver, base_uri) {#bytes-asposeslidesimportingiexternalresourceresolver-str}
Crée un nouvel objet SvgImage.

```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| data | **bytes** | Données Svg. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| base_uri | **str** | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

## __init__(self, svg_content, external_res_resolver, base_uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Crée un nouvel objet SvgImage.

```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| svg_content | **str** | Contenu Svg. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| base_uri | **str** | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

## __init__(self, stream, external_res_resolver, base_uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crée un nouvel objet SvgImage.

```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flux Svg. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| base_uri | **str** | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

### Voir aussi
* classe [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver)
* classe [`SvgImage`](/slides/python-net/fr/aspose.slides/svgimage)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)