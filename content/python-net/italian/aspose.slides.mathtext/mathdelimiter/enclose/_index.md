---
title: enclose method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Racchiude un elemento matematico tra parentesi

### Restituisce

L’elemento matematico di tipo [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter) che include la parentesi



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Racchiude un elemento matematico in caratteri specificati, come parentesi o altri caratteri come cornice

### Restituisce

Se `beginning_character` e `ending_character` sono None, 
            le proprietà corrispondenti ricevono valori solo e non viene creato un nuovo oggetto (restituisce questa istanza).
            Altrimenti, restituisce un nuovo elemento matematico di tipo Delimiter che include i caratteri specificati come cornice 
            e questa istanza di [`MathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter) incorniciata all’interno.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| beginning_character | **char** | Carattere iniziale (di solito parentesi quadra sinistra) |
| ending_character | **char** | Carattere finale (di solito parentesi quadra destra) |



### Vedi anche
* classe [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter)
* classe [`MathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)