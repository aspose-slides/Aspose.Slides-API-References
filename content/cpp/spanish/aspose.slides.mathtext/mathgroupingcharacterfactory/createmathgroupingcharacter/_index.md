---
title: CreateMathGroupingCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un carácter de agrupación matemática
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) método


Crea un carácter de agrupación matemática

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que aplicar el carácter de agrupación |
| character | char16_t | carácter de agrupación |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | posición del carácter de agrupación |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | justificación vertical |

### Valor devuelto

nuevo elemento de carácter de agrupación

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) método


Crea un carácter de agrupación matemática

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que aplicar el carácter de agrupación |

### Valor devuelto

nuevo elemento de carácter de agrupación

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)