---
title: get_BaseJustification()
second_title: Aspose.Slides per C++ Riferimento API
description: "Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center"
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() metodo


Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Osservazioni


Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Vedi anche

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)