---
title: Group()
second_title: Referência da API Aspose.Slides para C++
description: Coloca este elemento em um grupo usando um colchete curvo inferior
type: docs
weight: 235
url: /pt/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() método

Coloca este elemento em um grupo usando um colchete curvo inferior

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### Valor de retorno

Nova instância do tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Observações

Exemplo: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) método

Coloca este elemento em um grupo usando um caractere de agrupamento, como colchete curvo inferior ou outro

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| character | char16_t | Caractere de agrupamento como BOTTOM CURLY BRACKET (U+23DF) ou qualquer outro |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posição do caractere de agrupamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está na linha de base; quando VerticalJustification é definido como Bottom, a parte inferior do objeto está na linha de base |

### Valor de retorno

Nova instância do tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Observações

```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Veja também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)