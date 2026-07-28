---
title: get_AlignmentPoint()
second_title: Aspose.Slides dla C++: odniesienie API
description: "Gdy wartość jest prawdziwa, ten emulator operatora służy jako punkt wyrównania; oznacza to, że wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false"
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() metoda


When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Domyślnie: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Zobacz także

* Klasa [MathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)