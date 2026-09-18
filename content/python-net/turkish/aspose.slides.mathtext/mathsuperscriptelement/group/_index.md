---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Bu öğeyi bir grup içinde, alt kıvrımlı parantez kullanarak konumlandırır

### Döndürür

[`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde yeni bir örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi bir grup içinde, alt kıvrımlı parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak konumlandırır

### Döndürür

[`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde yeni bir örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) gibi bir GrUPLAMA karakteri veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalamasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üzerinde olduğunda, <br/><br/>            VerticalJustification'ın Top olması, nesnenin üst kısmının taban çizgisine denk geldiği anlamına gelir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı taban çizgisine tekabül eder |



### Ayrıca Bakınız
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathSuperscriptElement`](/slides/python-net/tr/aspose.slides.mathtext/mathsuperscriptelement)
* enum [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)