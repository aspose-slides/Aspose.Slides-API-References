---
title: enclose method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Bir matematik öğesini parantez içinde kapsar

### Dönüş Değeri

The math element of type [`IMathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/imathdelimiter) which includes the parenthesis



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveleyerek kapsar

### Dönüş Değeri

The math element of type [`IMathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| beginning_character | **char** | Başlangıç karakteri (genellikle sol köşeli parantez) |
| ending_character | **char** | Bitiş karakteri (genellikle sağ köşeli parantez) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveleyerek ve bir ayırıcı karakterle sınırlayarak kapsar

### Dönüş Değeri

The math element of type [`IMathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing and delimiter



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| beginning_character | **char** | Başlangıç karakteri (genellikle sol köşeli parantez) |
| ending_character | **char** | Bitiş karakteri (genellikle sağ köşeli parantez) |
| separator_character | **char** | Ayırıcı karakter |



### Ayrıca Bakınız
* sınıf [`IMathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/imathdelimiter)
* sınıf [`MathBlock`](/slides/python-net/tr/aspose.slides.mathtext/mathblock)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)