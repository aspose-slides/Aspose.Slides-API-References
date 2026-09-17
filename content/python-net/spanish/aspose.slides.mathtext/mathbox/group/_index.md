---
title: group method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathbox/group/
weight: 80
---
## group(self) {#}
Coloca este elemento en un grupo usando una llave rizada inferior

### Devuelve

Nueva instancia del tipo [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro

### Devuelve

Nueva instancia del tipo [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| character | **char** | Carácter de agrupación como LLAVE RIZADA INFERIOR (U+23DF) o cualquier otro |
| position | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Posición del carácter de agrupación |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Justificación vertical del carácter de grupo.<br/><br/>            Especifica la alineación del objeto con respecto a la línea base.<br/><br/>            Por ejemplo, cuando el carácter de grupo está encima del objeto, <br/><br/>            VerticalJustification de Top indica que la parte superior del objeto está en la línea base;<br/><br/>            cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base |

### Ver también
* clase [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)
* clase [`MathBox`](/slides/python-net/es/aspose.slides.mathtext/mathbox)
* enumeración [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)