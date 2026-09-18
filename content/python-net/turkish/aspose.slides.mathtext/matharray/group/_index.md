---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi alt süslü parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| character | **char** | Gruplama Karakteri, BOTTOM CURLY BRACKET (U+23DF) veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalanmasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üzerinde olduğunda, <br/><br/>            VerticalJustification of Top, nesnenin üst kısmının taban çizgisine denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı taban çizgisinde olur |



### Ayrıca Bakınız
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathArray`](/slides/python-net/tr/aspose.slides.mathtext/matharray)
* enumeration [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)