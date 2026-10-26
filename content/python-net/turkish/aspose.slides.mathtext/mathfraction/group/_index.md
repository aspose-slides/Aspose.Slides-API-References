---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathfraction/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir

### Returns
Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi alt süslü parantez gibi bir grup karakteri ya da başka bir karakter kullanarak bir gruba yerleştirir

### Returns
Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | Gruplama karakteri, BOTTOM CURLY BRACKET (U+23DF) gibi ya da başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalamasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üstünde olduğunda, <br/><br/>            VerticalJustification of Top, nesnenin üstünün taban çizgisine denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin altı taban çizgisine denk gelir |



### See Also
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathFraction`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction)
* enum [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)