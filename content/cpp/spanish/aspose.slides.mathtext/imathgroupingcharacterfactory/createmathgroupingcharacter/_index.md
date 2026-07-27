---
title: CreateMathGroupingCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un carácter de agrupación matemática
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) método


Crea un carácter de agrupación matemática

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
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

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) método


Crea un carácter de agrupación matemática

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
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
* Clase [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathGroupingCharacterFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)