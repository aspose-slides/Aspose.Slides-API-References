---
title: get_NoBreak()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Brak podziału. Ta właściwość określa właściwość \"niełamliwy\" w ramce obiektu. Gdy true, w ramce nie mogą wystąpić podziały wierszy. Może to być istotne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, podziały mogą wystąpić wewnątrz ramki. Domyślnie: true"
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() metoda


Brak podziału. Ta właściwość określa właściwość \"niełamliwy\" w ramce obiektu. Gdy true, w ramce nie mogą wystąpić podziały wierszy. Może to być istotne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, podziały mogą wystąpić wewnątrz ramki. Domyślnie: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Uwagi


Przykład:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Zobacz także

* Klasa [IMathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)