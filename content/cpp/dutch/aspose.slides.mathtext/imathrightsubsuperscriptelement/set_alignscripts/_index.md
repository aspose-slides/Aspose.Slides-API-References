---
title: set_AlignScripts()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de uitlijning van subscript/superscript. Wanneer true, zijn subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernd op de vorm van de basis. Standaardwaarde is false.
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) methode

Specificeert de uitlijning van subscript/superscript. Wanneer true, zijn subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernd op de vorm van de basis. Standaardwaarde is false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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