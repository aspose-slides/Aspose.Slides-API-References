---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathbox/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir

### Dönüş

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) örneği



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi alt süslü parantez gibi bir gruplama karakteri ya da başka bir karakter kullanarak bir gruba yerleştirir

### Dönüş

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) örneği



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | Gruplama Karakteri, BOTTOM CURLY BRACKET (U+23DF) gibi veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalanmasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üstünde olduğunda, <br/><br/>            Top değerindeki VerticalJustification, nesnenin üst kısmının taban çizgisine denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı taban çizgisindedir |



### İlgili
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathBox`](/slides/python-net/tr/aspose.slides.mathtext/mathbox)
* enum [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)