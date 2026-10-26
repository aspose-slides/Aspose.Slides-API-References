---
title: get_NoBreak()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Brak podziału Ta własność określa właściwość \"niepodzielna\" na obiekcie box. Gdy true, żadne podziały linii nie mogą wystąpić w obrębie boxa. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, podziały mogą wystąpić wewnątrz boxa. Domyślnie: true"
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() metoda


Brak podziału Ta własność określa właściwość \"niepodzielna\" na obiekcie box. Gdy true, żadne podziały linii nie mogą wystąpić w obrębie boxa. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, podziały mogą wystąpić wewnątrz boxa. Domyślnie: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Zobacz także

* Klasa [MathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)