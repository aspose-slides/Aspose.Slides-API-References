---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathblock/group/
weight: 130
---
## group(self) {#}
Bu öğeyi bir grup içinde, alt kıvırcık parantez kullanarak yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi bir gruplama karakteri (örneğin bottom curly bracket veya başka bir karakter) kullanarak bir gruba yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | Gruplama Karakteri, BOTTOM CURLY BRACKET (U+23DF) gibi veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalanmasını belirler.<br/><br/>            Örneğin, grup karakteri nesnenin üzerinde olduğunda, <br/><br/>            VerticalJustification of Top, nesnenin üst kısmının taban çizgisine oturduğunu gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı taban çizgisine oturur |



### Bakınız
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathBlock`](/slides/python-net/tr/aspose.slides.mathtext/mathblock)
* enumerasyon [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)