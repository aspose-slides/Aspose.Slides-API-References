---
title: group method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathematicaltext/group/
weight: 80
---
## group(self) {#}
Coloca este elemento en un grupo usando una llave rizada inferior

### Devuelve

New instance of type [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro

### Devuelve

New instance of type [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| character | **char** | Carácter de agrupación como BOTTOM CURLY BRACKET (U+23DF) o cualquier otro |
| position | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Posición del carácter de agrupación |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions) | Justificación vertical del carácter de grupo.<br/><br/>            Especifica la alineación del objeto respecto a la línea base.<br/><br/>            Por ejemplo, cuando el carácter de grupo está encima del objeto, <br/><br/>            VerticalJustification de Top indica que la parte superior del objeto está en la línea base;<br/><br/>            cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base |



### Ver también
* class [`IMathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathematicalText`](/slides/python-net/es/aspose.slides.mathtext/mathematicaltext)
* enumeration [`MathTopBotPositions`](/slides/python-net/es/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)