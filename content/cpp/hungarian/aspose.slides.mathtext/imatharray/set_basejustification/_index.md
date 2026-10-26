---
title: set_BaseJustification()
second_title: Aspose.Slides C++ API referencia
description: "Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömbobjektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) metódus

Meghatározza a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg igazítható a tömbobjektum aljához, tetejéhez vagy közepéhez. Alapértelmezett érték: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
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
* Library [Aspose.Slides](../../../)