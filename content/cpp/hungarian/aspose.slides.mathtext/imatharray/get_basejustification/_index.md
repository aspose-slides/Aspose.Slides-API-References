---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API-referencia
description: "Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() metódus

Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömb objektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Megjegyzések

Példa: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Lásd még

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Osztály [IMathArray](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)