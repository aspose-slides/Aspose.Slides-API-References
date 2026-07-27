---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um caractere de agrupamento matemático
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) método

Cria um caractere de agrupamento matemático

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o caractere de agrupamento |
| character | char16_t | caractere de agrupamento |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | posição do caractere de agrupamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | justificação vertical |

### Valor de retorno

novo elemento de caractere de agrupamento

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) método

Cria um caractere de agrupamento matemático

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o caractere de agrupamento |

### Valor de retorno

novo elemento de caractere de agrupamento

## Ver também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)