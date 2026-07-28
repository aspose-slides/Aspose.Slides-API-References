---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API Referencia
description: "Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() metódus

Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli Text igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
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