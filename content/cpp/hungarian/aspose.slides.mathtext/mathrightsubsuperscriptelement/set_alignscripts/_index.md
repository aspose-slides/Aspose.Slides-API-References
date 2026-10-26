---
title: set_AlignScripts()
second_title: Aspose.Slides C++ API referencia
description: Megadja az alsó index/felső index igazítását. Ha true, az alsó index és a felső index egymáshoz vízszintesen van igazítva. Ha false, a bázis alakjához kerülnek a kerning segítségével. Alapértelmezett érték false.
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) metódus


Megadja az alsó index/felső index igazítását. Ha true, az alsó index és a felső index egymáshoz vízszintesen van igazítva. Ha false, akkor a bázis alakjához kerülnek a kerning segítségével. Az alapértelmezett érték false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Megjegyzések


Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Lásd még

* Osztály [MathRightSubSuperscriptElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)