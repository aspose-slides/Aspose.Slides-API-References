---
title: Presentation constructor
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Deze constructor maakt een nieuwe presentatie vanaf nul.  
De gemaakte presentatie bevat één lege dia.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Deze constructor maakt een nieuwe presentatie vanaf nul.  
De gemaakte presentatie bevat één lege dia.

```python
def __init__(self, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/nl/aspose.slides/loadoptions) | Extra laadopties. |

## __init__(self, stream) {#iorawiobase}
Deze constructor is het primaire mechanisme om een bestaande Presentatie te lezen.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Invoerstroom. |

## __init__(self, file) {#str}
Deze constructor haalt een bronbestandspad op waarvan de inhoud van de Presentatie wordt gelezen.

```python
def __init__(self, file):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file | **str** | Invoerbestand. |

### Excepties

| Exceptie | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer het invoerbestand nul lengte heeft |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Deze constructor is het primaire mechanisme om een bestaande Presentatie te lezen.

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Invoerstroom. |
| load_options | [`LoadOptions`](/slides/python-net/nl/aspose.slides/loadoptions) | Extra laadopties. |

## __init__(self, file, load_options) {#str-loadoptions}
Deze constructor haalt een bronbestandspad op waarvan de inhoud van de Presentatie wordt gelezen.

```python
def __init__(self, file, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file | **str** | Invoerbestand. |
| load_options | [`LoadOptions`](/slides/python-net/nl/aspose.slides/loadoptions) | Extra laadopties. |

### Excepties

| Exceptie | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer het invoerbestand nul lengte heeft |

### Zie ook
* klasse [`LoadOptions`](/slides/python-net/nl/aspose.slides/loadoptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)