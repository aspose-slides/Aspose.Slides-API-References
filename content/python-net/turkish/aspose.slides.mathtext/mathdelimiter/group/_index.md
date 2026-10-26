---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
Bu öğeyi bir alt kıvrımlı parantez kullanarak bir gruba yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi, alt kıvrımlı parantez gibi bir gruplayıcı karakter veya başka bir karakter kullanarak bir gruba yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) gibi bir Gruplama Karakteri veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalanmasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üzerindeyse, <br/><br/>            VerticalJustification of Top, nesnenin üst kısmının taban çizgisine denk geldiğini gösterir;<br/><br/>            VerticalJustification is set to Bottom olduğunda, nesnenin alt kısmı taban çizgisindedir |



### Diğer
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter)
* enumerasyon [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)