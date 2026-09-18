---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir

### Döndürür

New instance of type [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi bir grup karakteri kullanarak bir gruba yerleştirir; örneğin alt kıvrımlı parantez veya başka bir karakter

### Döndürür

New instance of type [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) gibi bir Gruplama Karakteri veya başka bir şey |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Gruplama karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin taban çizgisine göre hizalamasını belirler.<br/><br/>            Örneğin, grup karakteri nesnenin üzerinde olduğunda , <br/><br/>            Top değeri, nesnenin üst kısmının taban çizgisine denk geldiğini gösterir;<br/><br/>            VerticalJustification değeri Bottom olarak ayarlandığında, nesnenin alt kısmı taban çizgisindedir |

### Ayrıca Bakınız
* class [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathRightSubSuperscriptElement`](/slides/python-net/tr/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)