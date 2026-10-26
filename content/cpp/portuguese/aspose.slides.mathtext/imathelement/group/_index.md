---
title: Group()
second_title: Referência da API Aspose.Slides para C++
description: Coloca este elemento em um grupo usando uma chave curvada inferior
type: docs
weight: 248
url: /pt/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() método

Coloca este elemento em um grupo usando uma chave curvada inferior

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### Valor de retorno

Nova instância do tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Observações



Exemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) método


Coloca este elemento em um grupo usando um caractere de agrupamento como chave curvada inferior ou outro

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| character | char16_t | Caractere de Agrupamento como BOTTOM CURLY BRACKET (U+23DF) ou qualquer outro |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posição do caractere de agrupamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justificação vertical do caractere de agrupamento. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de agrupamento está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base |

### Valor de retorno

Nova instância do tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Observações



Exemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Veja Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* classe [IMathElement](../)
* namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)