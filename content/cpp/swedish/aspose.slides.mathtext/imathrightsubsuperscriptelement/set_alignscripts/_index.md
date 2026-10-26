---
title: set_AlignScripts()
second_title: Aspose.Slides för C++ API-referens
description: Anger justeringen av nedsänkt text/upphöjd text. När true är nedsänkt text och upphöjd text horisontellt justerade mot varandra. När false är de anpassade till basens form. Standardvärdet är false.
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metod

Anger justeringen av nedsänkt text/upphöjd text. När true är nedsänkt text och upphöjd text horisontellt justerade mot varandra. När false är de anpassade till basens form. Standardvärdet är false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

* Klass [IMathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)