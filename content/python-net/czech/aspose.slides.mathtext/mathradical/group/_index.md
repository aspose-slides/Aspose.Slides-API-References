---
title: group method
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathradical/group/
weight: 80
---
## group(self) {#}
Umístí tento prvek do skupiny pomocí spodní složené závorky

### Vrací

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umístí tento prvek do skupiny pomocí skupinového znaku, například spodní složené závorky nebo jiného

### Vrací

Nová instance typu [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| character | **char** | Skupinový znak, například spodní složená závorka (U+23DF) nebo jiný |
| position | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Pozice skupinového znaku |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions) | Vertikální zarovnání grupovacího znaku.<br/><br/>            Specifikuje zarovnání objektu vzhledem k základní linii.<br/><br/>            Například když je grupovací znak nad objektem, <br/><br/>            Vertikální zarovnání Top znamená, že horní část objektu leží na základní linii;<br/><br/>            když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu je na základní linii |

### Viz také
* třída [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter)
* třída [`MathRadical`](/slides/python-net/cs/aspose.slides.mathtext/mathradical)
* enumerace [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)