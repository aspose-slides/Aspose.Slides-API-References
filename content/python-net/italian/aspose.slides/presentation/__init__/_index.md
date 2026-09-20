---
title: Presentation constructor
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Questo costruttore crea una nuova presentazione da zero.
            La presentazione creata ha una diapositiva vuota.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Questo costruttore crea una nuova presentazione da zero.
            La presentazione creata ha una diapositiva vuota.

```python
def __init__(self, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/it/aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

## __init__(self, stream) {#iorawiobase}
Questo costruttore è il meccanismo principale per leggere una presentazione esistente.

```python
def __init__(self, stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream di input. |

## __init__(self, file) {#str}
Questo costruttore ottiene un percorso di file sorgente da cui i contenuti della presentazione sono letti.

```python
def __init__(self, file):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file | **str** | File di input. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata quando il file di input ha lunghezza zero |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Questo costruttore è il meccanismo principale per leggere una presentazione esistente.

```python
def __init__(self, stream, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream di input. |
| load_options | [`LoadOptions`](/slides/python-net/it/aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

## __init__(self, file, load_options) {#str-loadoptions}
Questo costruttore ottiene un percorso di file sorgente da cui i contenuti della presentazione sono letti.

```python
def __init__(self, file, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file | **str** | File di input. |
| load_options | [`LoadOptions`](/slides/python-net/it/aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata quando il file di input ha lunghezza zero |

### Vedi anche
* classe [`LoadOptions`](/slides/python-net/it/aspose.slides/loadoptions)
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)