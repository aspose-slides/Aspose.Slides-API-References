---
title: group method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
Place cet élément dans un groupe en utilisant une accolade basse

### Renvoie

Nouvelle instance du type [`IMathGroupingCharacter`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade basse ou un autre

### Renvoie

Nouvelle instance du type [`IMathGroupingCharacter`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| character | **char** | Caractère de groupement tel qu'ACCOLADE BASSE (U+23DF) ou tout autre |
| position | [`MathTopBotPositions`](/slides/python-net/fr/aspose.slides.mathtext/mathtopbotpositions) | Position du caractère de groupement |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fr/aspose.slides.mathtext/mathtopbotpositions) | Justification verticale du caractère de groupe.<br/><br/>            Spécifie l'alignement de l'objet par rapport à la ligne de base.<br/><br/>            Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, <br/><br/>            VerticalJustification de Top indique que le haut de l'objet se situe sur la ligne de base;<br/><br/>            lorsque VerticalJustification est défini sur Bottom, le bas de l'objet se trouve sur la ligne de base |



### Voir aussi
* classe [`IMathGroupingCharacter`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter)
* classe [`MathRightSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* énumération [`MathTopBotPositions`](/slides/python-net/fr/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)