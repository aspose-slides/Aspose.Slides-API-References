---
title: get_AlignmentPoint()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Kiedy jest ustawione na true, ten emulator operatora działa jako punkt wyrównania; tzn., wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false"
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() metoda


Kiedy jest ustawione na true, ten emulator operatora działa jako punkt wyrównania; tzn., wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Zobacz także

* Klasa [IMathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)