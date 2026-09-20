---
title: enclose method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Racchiude un elemento matematico tra parentesi

### Restituisce

L'elemento matematico di tipo [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter) che include le parentesi



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come le parentesi o altri caratteri, come cornice

### Restituisce

L'elemento matematico di tipo [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter) che include i caratteri specificati come cornice



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| beginning_character | **char** | Carattere iniziale (di solito parentesi quadra sinistra) |
| ending_character | **char** | Carattere finale (di solito parentesi quadra destra) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come le parentesi o altri, come cornice e li delimita con un carattere separatore

### Restituisce

L'elemento matematico di tipo [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter) che include i caratteri specificati come cornice e delimitatore



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| beginning_character | **char** | Carattere iniziale (di solito parentesi quadra sinistra) |
| ending_character | **char** | Carattere finale (di solito parentesi quadra destra) |
| separator_character | **char** | Carattere separatore |



### Vedi anche
* classe [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter)
* classe [`MathBlock`](/slides/python-net/it/aspose.slides.mathtext/mathblock)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)