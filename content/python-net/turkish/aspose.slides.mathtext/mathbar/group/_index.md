---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathbar/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt kıvırcık parantez kullanarak bir grupta yerleştirir

### Dönüş Değeri

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi alt kıvırcık parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir grupta yerleştirir

### Dönüş Değeri

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Position of grouping character |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalamasını belirler.<br/><br/>            Örneğin, grup karakteri nesnenin üzerindeyken, <br/><br/>            VerticalJustification of Top, nesnenin üst kısmının taban çizgisine denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı taban çizgisindedir |



### Ayrıca Bakınız
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathBar`](/slides/python-net/tr/aspose.slides.mathtext/mathbar)
* enumerasyon [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)