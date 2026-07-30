---
title: set_VerticalJustification()
second_title: Riferimento API di Aspose.Slides per C++
description: "Allineamento verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base Predefinito: Bottom per Position=Top e Top per Position=Bottom"
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metodo


Allineamento verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto si trova sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto si trova sulla linea di base Predefinito: Bottom per Position=Top e Top per Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Osservazioni


Esempio: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Vedere anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathGroupingCharacter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)