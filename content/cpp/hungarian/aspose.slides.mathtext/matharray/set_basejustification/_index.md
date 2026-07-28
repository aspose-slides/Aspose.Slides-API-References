---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API-referencia
description: "Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg a tömbobjektum aljához, tetejéhez vagy közepéhez igazítható. Alapértelmezett érték: Center"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) metódus


Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg az aljához, tetejéhez vagy egy tömbobjektum közepéhez igazítható. Alapértelmezett érték: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Megjegyzések


Példa: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Lásd még

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Osztály [MathArray](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)