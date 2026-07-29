---
title: get_AlignScripts()
second_title: Aspose.Slides för C++ API-referens
description: Specificerar justeringen av subscript/superscript. När true, subscript och superscript är horisontellt justerade mot varandra. När false, kerna de till basens form. Standardvärdet är false.
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metod


Specificerar justeringen av subscript/superscript. När true, subscript och superscript är horisontellt justerade mot varandra. När false, kerna de till basens form. Standardvärdet är false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

* Klass [MathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)