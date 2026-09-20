---
title: enclose method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/imathblock/enclose/
weight: 90
---
## enclose(self) {#}

```python
def enclose(self):
    ...
```

## enclose(self, beginning_character, ending_character) {#char-char}

```python
def enclose(self, beginning_character, ending_character):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| beginning_character | **char** |  |
| ending_character | **char** |  |

## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Raccoglie gli elementi figli di questo blocco nei caratteri specificati, ad esempio parentesi o altri, come incorniciatura, e li delimita con un carattere separatore

### Restituisce
L'elemento matematico di tipo [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter) che include i caratteri specificati come incorniciatura e delimitatore

```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| beginning_character | **char** | Carattere iniziale (di solito parentesi sinistra) |
| ending_character | **char** | Carattere finale (di solito parentesi destra) |
| separator_character | **char** | Carattere separatore |

### Vedi anche
* classe [`IMathBlock`](/slides/python-net/it/aspose.slides.mathtext/imathblock)
* classe [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)