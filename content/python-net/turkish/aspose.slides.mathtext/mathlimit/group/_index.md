---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Bu öğeyi bir alt kıvrımlı ayraç kullanarak bir gruba yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi, alt kıvrımlı ayraç veya başka bir karakter gibi bir gruplandırma karakteri kullanarak bir gruba yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | Grup Karakteri, BOTTOM CURLY BRACKET (U+23DF) gibi veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin temel çizgiye göre hizalamasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üstünde olduğunda, <br/><br/>            Üst VerticalJustification, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgi üzerindedir |



### Ayrıca Bakınız
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathLimit`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit)
* enumeration [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)