---
title: Group()
second_title: Riferimento API di Aspose.Slides per C++
description: Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore
type: docs
weight: 248
url: /it/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() method


Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Return Value

Nuova istanza del tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Osservazioni



Esempio: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) method


Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come una parentesi graffa inferiore o un altro

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Carattere di raggruppamento come BOTTOM CURLY BRACKET (U+23DF) o qualsiasi altro |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posizione del carattere di raggruppamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Allineamento verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Per esempio, quando il carattere di gruppo è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto si trova sulla linea di base |

### Return Value

Nuova istanza del tipo [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Osservazioni



Esempio: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)