---
title: group method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
Coloca este elemento en un grupo usando una llave curva inferior

### Devuelve
Nueva instancia del tipo [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Coloca este elemento en un grupo usando un carácter de agrupamiento como una llave curva inferior u otro

### Devuelve
Nueva instancia del tipo [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| character | **char** | Carácter de agrupamiento como LLAVE CURVA INFERIOR (U+23DF) o cualquier otro |
| position | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Posición del carácter de agrupamiento |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Justificación vertical del carácter de grupo.<br/><br/>            Especifica la alineación del objeto con respecto a la línea base.<br/><br/>            Por ejemplo, cuando el carácter de grupo está encima del objeto, <br/><br/>            VerticalJustification de Top indica que la parte superior del objeto cae en la línea base;<br/><br/>            cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base |

### Ver también
* class [`BaseScript`](/slides/python-net/es/aspose.slides.mathtext/basescript)
* class [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)