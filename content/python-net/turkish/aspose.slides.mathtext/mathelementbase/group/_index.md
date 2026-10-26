---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathelementbase/group/
weight: 70
---
## group(self) {#}
Bu öğeyi alt kıvırcık parantez kullanarak bir gruba yerleştirir

### Returns
[`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde yeni bir örnek

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi, alt kıvırcık parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir

### Returns
[`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) tipinde yeni bir örnek

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) gibi bir Grup Karakteri veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin temel çizgiye göre hizalanmasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üzerindeyse,<br/><br/>            VerticalJustification'un Top olması, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide bulunur |

### See Also
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* enumeration [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)