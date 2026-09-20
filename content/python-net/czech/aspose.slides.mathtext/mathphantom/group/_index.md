---
title: group method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí spodní složené závorky

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí grupovacího znaku, například spodní složené závorky nebo jiného znaku

### Návratová hodnota

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Skupinový znak, například BOTTOM CURLY BRACKET (U+23DF) nebo libovolný jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice grupovacího znaku |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání grupovacího znaku.<br/><br/>            Určuje zarovnání objektu vzhledem k referenční čáře.<br/><br/>            Například když je grupovací znak nad objektem, <br/><br/>            VerticalJustification of Top znamená, že horní část objektu leží na referenční čáře;<br/><br/>            když je VerticalJustification nastaveno na Bottom, spodní část objektu je na referenční čáře |



### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathPhantom`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)