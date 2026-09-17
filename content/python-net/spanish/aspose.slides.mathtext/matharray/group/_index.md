---
title: group method
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/matharray/group/
weight: 80
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
Coloca este elemento en un grupo usando un carácter de agrupación como la llave curva inferior u otro

### Devuelve

Nueva instancia del tipo [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| character | **char** | Carácter de agrupación como LLAVE CURVA INFERIOR (U+23DF) u otro |
| position | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Posición del carácter de agrupación |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Justificación vertical del carácter de grupo.<br/><br/>            Especifica la alineación del objeto con respecto a la línea base.<br/><br/>            Por ejemplo, cuando el carácter de grupo está sobre el objeto, <br/><br/>            VerticalJustification de Top indica que la parte superior del objeto se encuentra en la línea base;<br/><br/>            cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base |



### Véase también
* clase [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)
* clase [`MathArray`](/slides/python-net/es/aspose.slides.mathtext/matharray)
* enumeración [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)