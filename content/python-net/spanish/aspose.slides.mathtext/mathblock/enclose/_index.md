---
title: enclose method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Encierra un elemento matemático entre paréntesis

### Devuelve

El elemento matemático de tipo [`IMathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiter) que incluye los paréntesis



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros caracteres como marco

### Devuelve

El elemento matemático de tipo [`IMathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiter) que incluye los caracteres especificados como marco



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| beginning_character | **char** | Carácter de inicio (usualmente corchete izquierdo) |
| ending_character | **char** | Carácter de fin (usualmente corchete derecho) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros como marco y los delimita con un carácter separador

### Devuelve

El elemento matemático de tipo [`IMathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiter) que incluye los caracteres especificados como marco y delimitador



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| beginning_character | **char** | Carácter de inicio (usualmente corchete izquierdo) |
| ending_character | **char** | Carácter de fin (usualmente corchete derecho) |
| separator_character | **char** | Carácter separador |



### Ver también
* clase [`IMathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiter)
* clase [`MathBlock`](/slides/python-net/es/aspose.slides.mathtext/mathblock)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)