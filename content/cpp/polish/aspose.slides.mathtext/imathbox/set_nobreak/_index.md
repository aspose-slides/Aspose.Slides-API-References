---
title: set_NoBreak()
second_title: Aspose.Slides – odniesienie API C++
description: "Brak podziału. Ta właściwość określa właściwość \"unbreakable\" w obiekcie pudełka. Gdy jest ustawiona na true, w obrębie pudełka nie mogą wystąpić podziały linii. Może to być ważne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Jeśli ten element nie zostanie określony, podziały mogą wystąpić wewnątrz pudełka. Domyślnie: true"
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) metoda


Brak podziału. Ta właściwość określa właściwość "unbreakable" w obiekcie pudełka. Gdy jest ustawiona na true, w obrębie pudełka nie mogą wystąpić podziały linii. Może to być istotne dla emulatorów operatorów, które składają się z więcej niż jednego operatora binarnego. Jeśli ten element nie zostanie określony, podziały mogą wystąpić wewnątrz pudełka. Domyślnie: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
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