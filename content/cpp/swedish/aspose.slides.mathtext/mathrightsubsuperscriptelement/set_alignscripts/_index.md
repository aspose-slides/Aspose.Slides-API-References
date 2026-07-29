---
title: set_AlignScripts()
second_title: Aspose.Slides för C++ API-referens
description: Anger justeringen av nedsänkt/upphöjt. När true är nedsänkt och upphöjt horisontellt justerade mot varandra. När false är de kerna till basens form. Standardvärdet är false.
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) metod


Anger justeringen av nedsänkt/upphöjt tecken. När true är nedsänkt och upphöjt horisontellt justerade mot varandra. När false är de kerna till basens form. Standardvärdet är false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Anmärkningar


Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Se också

* Klass [MathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)