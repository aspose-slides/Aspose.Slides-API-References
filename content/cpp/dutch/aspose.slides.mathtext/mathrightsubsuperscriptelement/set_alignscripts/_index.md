---
title: set_AlignScripts()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de uitlijning van subscript/superscript. Wanneer true, worden subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze aangepast aan de vorm van de basis. Standaardwaarde is false.
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) methode

Specificeert de uitlijning van subscript/superscript. Wanneer true, worden subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze aangepast aan de vorm van de basis. Standaardwaarde is false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)