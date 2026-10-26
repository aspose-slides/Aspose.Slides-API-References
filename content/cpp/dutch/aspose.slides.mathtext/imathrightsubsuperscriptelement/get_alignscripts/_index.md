---
title: get_AlignScripts()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de uitlijning van subscript/superscript. Wanneer true, worden subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernd naar de vorm van de basis. Standaardwaarde is false.
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() methode


Specificeert de uitlijning van subscript/superscript. Wanneer true, worden subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze naar de vorm van de basis gekernd. Standaardwaarde is false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

* Klasse [IMathRightSubSuperscriptElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)