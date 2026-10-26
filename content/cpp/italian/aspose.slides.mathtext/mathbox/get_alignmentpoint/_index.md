---
title: get_AlignmentPoint()
second_title: Riferimento API Aspose.Slides per C++
description: "Quando true, questo emulatore di operatore serve come punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Predefinito: false"
type: docs
weight: 92
url: /it/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() metodo

Quando true, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Predefinito: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Osservazioni

Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Vedi anche

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)