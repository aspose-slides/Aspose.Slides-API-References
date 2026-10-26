---
title: get_AlignScripts()
second_title: Aspose.Slides C++ API referenciája
description: Megadja az alsó index/felső index igazítását. Ha igaz, az alsó index és a felső index vízszintesen egymáshoz igazítva jelenik meg. Ha hamis, a két index a bázis alakjához igazodik. Az alapértelmezett érték hamis.
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metódus


Megadja az alsó index/felső index igazítását. Ha igaz, az alsó index és a felső index vízszintesen egymáshoz igazítva jelenik meg. Ha hamis, a két index a bázis alakjához igazodik. Az alapértelmezett érték a hamis.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

* osztály [MathRightSubSuperscriptElement](../)
* névtér [Aspose::Slides::MathText](../../)
* könyvtár [Aspose.Slides](../../../)