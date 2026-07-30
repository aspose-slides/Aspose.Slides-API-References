---
title: get_Position()
second_title: Riferimento API Aspose.Slides per C++
description: "Posizione della linea della barra. Predefinito: Top"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() metodo

Posizione della linea della barra. Predefinito: Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## Osservazioni

Esempio: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathBar](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)