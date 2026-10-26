---
title: group method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
Bu öğeyi alt kıvırcık parantez kullanarak bir gruba yerleştirir

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) türünden bir örnek



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Bu öğeyi grup karakteri kullanarak bir gruba yerleştirir; örneğin alt kıvırcık parantez veya başka bir karakter

### Döndürür

Yeni [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter) türünden bir örnek



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| character | **char** | Grup Karakteri, örneğin BOTTOM CURLY BRACKET (U+23DF) veya başka bir karakter |
| position | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin konumu |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions) | Grup karakterinin dikey hizalaması.<br/><br/>            Nesnenin temel çizgiye göre hizalanmasını belirtir.<br/><br/>            Örneğin, grup karakteri nesnenin üzerindeyse, <br/><br/>            VerticalJustification of Top, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir;<br/><br/>            VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur |



### Diğer
* sınıf [`IMathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/imathgroupingcharacter)
* sınıf [`MathAccent`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent)
* enumerasyon [`MathTopBotPositions`](/slides/python-net/tr/aspose.slides.mathtext/mathtopbotpositions)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)