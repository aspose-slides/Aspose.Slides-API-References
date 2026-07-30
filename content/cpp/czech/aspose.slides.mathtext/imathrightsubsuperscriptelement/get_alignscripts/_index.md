---
title: get_AlignScripts()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Specifikuje zarovnání dolního a horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány k sobě. Když je false, jsou kernovány do tvaru základu. Výchozí hodnota je false.
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() method


Specifikuje zarovnání dolního a horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány k sobě. Když je false, jsou kernovány do tvaru základu. Výchozí hodnota je false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## Poznámky


Příklad:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Viz také

* Třída [IMathRightSubSuperscriptElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)