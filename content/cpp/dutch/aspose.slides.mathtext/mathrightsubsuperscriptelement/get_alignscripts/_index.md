---
title: get_AlignScripts()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de uitlijning van subscript/superscript aan. Wanneer true, zijn subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernd op de vorm van de basis. Standaardwaarde is false.
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() methode

Geeft de uitlijning van subscript/superscript aan. Wanneer true, subscript en superscript worden horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernerd op de vorm van de basis. Standaardwaarde is false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Zie ook

* Klasse [MathRightSubSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)