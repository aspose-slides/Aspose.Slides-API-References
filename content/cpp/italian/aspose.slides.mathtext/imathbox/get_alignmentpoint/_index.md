---
title: get_AlignmentPoint()
second_title: Riferimento API di Aspose.Slides per C++
description: "Quando è vero, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Predefinito: false"
type: docs
weight: 92
url: /it/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() metodo


Quando è vero, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Predefinito: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Vedi anche

* Classe [IMathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)