---
title: set_AlignScripts()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje zarovnání dolního a horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány vůči sobě. Když je false, jsou kerningově přizpůsobeny tvaru základny. Výchozí hodnota je false.
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metoda

Určuje zarovnání dolního a horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány vůči sobě. Když je false, jsou kerningově přizpůsobeny tvaru základny. Výchozí hodnota je false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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