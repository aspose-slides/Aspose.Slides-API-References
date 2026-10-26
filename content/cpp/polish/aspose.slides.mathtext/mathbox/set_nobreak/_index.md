---
title: set_NoBreak()
second_title: Aspose.Slides dla C++ – odwołanie do API
description: "Brak podziału Ta właściwość określa właściwość \"niełamliwe\" na obiekcie pudełka. Gdy jest ustawiona na true, żadne podziały linii nie mogą wystąpić wewnątrz pudełka. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, podziały mogą wystąpić wewnątrz pudełka. Domyślnie: true"
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) metoda


Brak podziału Ta właściwość określa właściwość "unbreakable" na obiekcie pudełka. Gdy jest ustawiona na true, żadne podziały linii nie mogą wystąpić wewnątrz pudełka. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Gdy ten element nie jest określony, podziały mogą wystąpić wewnątrz pudełka. Domyślnie: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
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