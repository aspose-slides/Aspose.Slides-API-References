---
title: enclose method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Bir matematik öğesini parantez içinde kapsar

### Returns

Parantezi içeren [`IMathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/imathdelimiter) türündeki matematik öğesi



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeveleyerek kapsar

### Returns

`beginning_character` ve `ending_character` None ise, ilgili özelliklere yalnızca değer atanır ve yeni bir nesne oluşturulmaz (bu örnek döndürülür). 
Aksi takdirde, belirtilen karakterleri çerçeve olarak içeren Delimiter türünde yeni bir matematik öğesi döndürür ve bu [`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter) örneği içinde çerçevelenmiş olarak yer alır.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| beginning_character | **char** | Başlangıç karakteri (genellikle sol köşeli parantez) |
| ending_character | **char** | Bitiş karakteri (genellikle sağ köşeli parantez) |



### Ayrıca Bakınız
* sınıf [`IMathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/imathdelimiter)
* sınıf [`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)