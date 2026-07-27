---
title: CreateMathGroupingCharacter()
second_title: Referência da API Aspose.Slides para C++
description: Cria um caractere de agrupamento matemático
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) método


Cria um caractere de agrupamento matemático

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o caractere de agrupamento |
| character | char16_t | caractere de agrupamento |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | posição do caractere de agrupamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | justificação vertical |

### Return Value

novo elemento de caractere de agrupamento

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) método


Cria um caractere de agrupamento matemático

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o caractere de agrupamento |

### Return Value

novo elemento de caractere de agrupamento

## Veja Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)