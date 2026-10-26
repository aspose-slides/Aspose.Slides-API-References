---
title: get_VerticalJustification()
second_title: Aspose.Slides per C++ API Reference
description: "Allineamento verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base Predefinito: Bottom per Position=Top e Top per Position=Bottom"
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() metodo

Allineamento verticale del carattere di gruppo. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base. Predefinito: Bottom per Position=Top e Top per Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Osservazioni

Esempio: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathGroupingCharacter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)