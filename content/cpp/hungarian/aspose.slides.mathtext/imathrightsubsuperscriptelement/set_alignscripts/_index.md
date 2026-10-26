---
title: set_AlignScripts()
second_title: Aspose.Slides for C++ API-referencia
description: Megadja az alsó index/felső index igazítását. Ha igaz, az alsó index és a felső index egymáshoz vízszintesen lesznek igazítva. Ha hamis, a bázishoz lesz kerningezve. Alapértelmezett érték a hamis.
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metódus


Meghatározza az alsó index/felső index igazítását. Ha igaz, az alsó index és a felső index egymáshoz vízszintesen lesznek igazítva. Ha hamis, a bázis alakjához lesz kerningezve. Alapértelmezett érték a hamis.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## Megjegyzés


Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Lásd még

* Osztály [IMathRightSubSuperscriptElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)