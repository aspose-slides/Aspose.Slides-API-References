---
title: Group()
second_title: Referencia de API de Aspose.Slides para C++
description: Coloca este elemento en un grupo usando una llave rizada inferior
type: docs
weight: 248
url: /es/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() método


Coloca este elemento en un grupo usando una llave rizada inferior

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Valor devuelto

Nueva instancia del tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Observaciones



Ejemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) método


Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| character | char16_t | Carácter de agrupación como BOTTOM CURLY BRACKET (U+23DF) u otro |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posición del carácter de agrupación |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justificación vertical del carácter de agrupación. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de agrupación está sobre el objeto, VerticalJustification de Top indica que la parte superior del objeto cae en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base |

### Valor devuelto

Nueva instancia del tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Observaciones



Ejemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)