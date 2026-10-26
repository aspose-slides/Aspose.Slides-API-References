---
title: enclose method
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Otacza element matematyczny nawiasami

### Zwraca

Element matematyczny typu [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter) który zawiera nawiasy



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne znaki, jako obramowanie

### Zwraca

Element matematyczny typu [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter) który zawiera określone znaki jako obramowanie



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| beginning_character | **char** | Znak początkowy (zazwyczaj lewy nawias) |
| ending_character | **char** | Znak końcowy (zazwyczaj prawy nawias) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne, jako obramowanie i oddziela je znakiem separatora

### Zwraca

Element matematyczny typu [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter) który zawiera określone znaki jako obramowanie i separator



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| beginning_character | **char** | Znak początkowy (zazwyczaj lewy nawias) |
| ending_character | **char** | Znak końcowy (zazwyczaj prawy nawias) |
| separator_character | **char** | Znak separatora |



### Zobacz także
* klasa [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter)
* klasa [`MathBlock`](/slides/python-net/pl/aspose.slides.mathtext/mathblock)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)