---
title: get_AlignScripts()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatározza az alsó index/felső index igazítását. Ha true, az alsó index és a felső index vízszintesen egymáshoz igazítva van. Ha false, a bázis alakjához vannak igazítva. Az alapértelmezett érték false.
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() metódus


Megadja az alsó index/felső index igazítását. Ha true, az alsó index és a felső index vízszintesen egymáshoz igazítva van. Ha false, azok a bázis alakjához vannak igazítva. Az alapértelmezett érték false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

* Osztály [IMathRightSubSuperscriptElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)