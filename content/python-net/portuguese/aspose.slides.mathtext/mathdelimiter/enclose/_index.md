---
title: enclose method
second_title: Referência da API Aspose.Slides para Python via .NET
description:
type: docs
url: /pt/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
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
Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura

### Retorna

Se `beginning_character` e `ending_character` forem None, 
            as propriedades correspondentes recebem apenas valores e nenhum novo objeto é criado (retorna esta instância).
            Caso contrário, retorna um novo elemento matemático do tipo Delimiter que inclui os caracteres especificados como moldura 
            e esta instância de [`MathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/mathdelimiter) enquadrada dentro.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| beginning_character | **char** | Caractere inicial (geralmente colchete esquerdo) |
| ending_character | **char** | Caractere final (geralmente colchete direito) |



### Veja Também
* classe [`IMathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/imathdelimiter)
* classe [`MathDelimiter`](/slides/python-net/pt/aspose.slides.mathtext/mathdelimiter)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)