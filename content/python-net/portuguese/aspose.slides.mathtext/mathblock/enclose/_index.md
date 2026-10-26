---
title: enclose method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Envolve um elemento matemático entre parênteses

### Retorna

O elemento matemático do tipo [`IMathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiter) que inclui os parênteses



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros caracteres como moldura

### Retorna

O elemento matemático do tipo [`IMathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiter) que inclui os caracteres especificados como moldura



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| beginning_character | **char** | Caractere inicial (geralmente colchete esquerdo) |
| ending_character | **char** | Caractere final (geralmente colchete direito) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros como moldura e delimita com um caractere separador

### Retorna

O elemento matemático do tipo [`IMathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiter) que inclui os caracteres especificados como moldura e delimitador



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| beginning_character | **char** | Caractere inicial (geralmente colchete esquerdo) |
| ending_character | **char** | Caractere final (geralmente colchete direito) |
| separator_character | **char** | Caractere separador |



### Veja Também
* classe [`IMathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiter)
* classe [`MathBlock`](/slides/python-net/pt/aspose.slides.mathtext/mathblock)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)