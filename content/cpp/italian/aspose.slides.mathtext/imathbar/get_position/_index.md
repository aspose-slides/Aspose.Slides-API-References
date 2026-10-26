---
title: get_Position()
second_title: Riferimento API Aspose.Slides per C++
description: "Posizione della linea della barra. Predefinito: Top"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() metodo


Posizione della linea della barra. Predefinito: Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Osservazioni

Esempio: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathBar](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)