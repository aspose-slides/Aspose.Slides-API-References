---
title: get_AlignScripts()
second_title: Aspose.Slides för C++ API-referens
description: Anger justeringen av nedsänkt/upphöjt. När sant är nedsänkt och upphöjt horisontellt inriktade mot varandra. När falskt justeras de efter basens form. Standardvärdet är falskt.
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMMathRightSubSuperscriptElement::get_AlignScripts() metod


Anger justeringen av nedsänkt/upphöjt. När sant är nedsänkt och upphöjt horisontellt inriktade mot varandra. När falskt justeras de efter basens form. Standardvärdet är falskt.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

## Se även

* Klass [IMathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)