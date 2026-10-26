---
title: enclose method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
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
Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco

### Devuelve

Si `beginning_character` y `ending_character` son None, 
            las propiedades correspondientes solo reciben valores y no se crea un nuevo objeto (devuelve esta instancia).
            De lo contrario, devuelve un nuevo elemento matemático del tipo Delimiter que incluye los caracteres especificados como marco 
            y esta instancia de [`MathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter) enmarcada dentro.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| beginning_character | **char** | Carácter inicial (usualmente corchete izquierdo) |
| ending_character | **char** | Carácter final (usualmente corchete derecho) |



### Ver también
* clase [`IMathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/imathdelimiter)
* clase [`MathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)