---
title: group method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
Coloca este elemento em um grupo usando uma chave curva inferior

### Retorna

Nova instância do tipo [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Coloca este elemento em um grupo usando um caractere de agrupamento, como chave curva inferior ou outro

### Retorna

Nova instância do tipo [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| character | **char** | Caractere de agrupamento como CHAVE CURVA INFERIOR (U+23DF) ou qualquer outro |
| position | [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions) | Posição do caractere de agrupamento |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions) | Justificação vertical do caractere de grupo.<br/><br/>            Especifica o alinhamento do objeto em relação à linha de base.<br/><br/>            Por exemplo, quando o caractere de grupo está acima do objeto, <br/><br/>            VerticalJustification de Top indica que a parte superior do objeto está na linha de base;<br/><br/>            quando VerticalJustification é definido como Bottom, a parte inferior do objeto está na linha de base |

### Veja Também
* classe [`IMathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/imathgroupingcharacter)
* classe [`MathAccent`](/slides/python-net/pt/aspose.slides.mathtext/mathaccent)
* enumeração [`MathTopBotPositions`](/slides/python-net/pt/aspose.slides.mathtext/mathtopbotpositions)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)