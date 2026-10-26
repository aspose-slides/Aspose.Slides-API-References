---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathnaryoperator/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt süslü parantez kullanarak bir grupta yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi alt süslü parantez gibi bir gruplama karakteri ya da başka bir karakter kullanarak bir grupta yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde bir örnek

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | Gruplama Karakteri, BOTTOM CURLY BRACKET (U+23DF) veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin temel çizgiye göre hizalanmasını belirler.<br/><br/>            Örneğin, grup karakteri nesnenin üzerindeyse, <br/><br/>            Top değerindeki VerticalJustification, nesnenin üstünün temel çizgiye denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin altı temel çizgide olur |

### Ayrıca Bakınız
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathNaryOperator`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator)
* enum [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)