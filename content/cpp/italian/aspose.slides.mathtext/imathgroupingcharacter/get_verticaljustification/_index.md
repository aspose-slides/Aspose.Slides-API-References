---
title: get_VerticalJustification()
second_title: Riferimento API di Aspose.Slides per C++
description: "Giustificazione verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base Predefinito: Bottom per Position=Top, e Top per Position=Bottom"
type: docs
weight: 66
url: /it/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metodo

Giustificazione verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Per esempio, quando il carattere di gruppo si trova sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base Predefinito: Bottom per Position=Top, e Top per Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Osservazioni

Esempio:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)