---
title: Group()
second_title: Riferimento API di Aspose.Slides per C++
description: Posiziona questo elemento in un gruppo utilizzando una parentesi graffa inferiore
type: docs
weight: 235
url: /it/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metodo

Places this element in a group using a bottom curly bracket

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### Valore di ritorno

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Osservazioni



Example: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metodo


Places this element in a group using a grouping character such as bottom curly bracket or another

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posizione del carattere di raggruppamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Giustificazione verticale del carattere di raggruppamento. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Per esempio, quando il carattere di raggruppamento è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto si trova sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base |

### Valore di ritorno

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Osservazioni



Example: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Classe [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)