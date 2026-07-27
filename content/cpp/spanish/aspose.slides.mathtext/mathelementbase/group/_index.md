---
title: Group()
second_title: Referencia de la API de Aspose.Slides para C++
description: Coloca este elemento en un grupo usando una llave rizada inferior
type: docs
weight: 235
url: /es/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() método

Coloca este elemento en un grupo usando una llave rizada inferior

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### Valor devuelto

Nueva instancia del tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Observaciones



Ejemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) método

Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Carácter de agrupación como LLAVE RIZADA INFERIOR (U+23DF) u otro |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posición del carácter de agrupación |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se encuentra en la línea base; cuando VerticalJustification se establece a Bottom, la parte inferior del objeto está en la línea base |

### Valor devuelto

Nueva instancia del tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Observaciones



Ejemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Véase también

* Enumeración [MathTopBotPositions](../../mathtopbotpositions/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Clase [MathElementBase](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)