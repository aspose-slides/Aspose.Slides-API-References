---
title: CreateMathGroupingCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un carattere di raggruppamento matematico
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metodo

Crea un carattere di raggruppamento matematico

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare il carattere di raggruppamento |
| character | char16_t | carattere di raggruppamento |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | posizione del carattere di raggruppamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | giustificazione verticale |

### Valore di ritorno

nuovo elemento di carattere di raggruppamento

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metodo

Crea un carattere di raggruppamento matematico

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare il carattere di raggruppamento |

### Valore di ritorno

nuovo elemento di carattere di raggruppamento

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathGroupingCharacterFactory](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)