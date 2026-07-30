---
title: set_BaseJustification()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center"
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) metodo

Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Vedi anche

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)