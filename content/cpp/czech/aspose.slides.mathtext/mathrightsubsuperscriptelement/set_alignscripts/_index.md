---
title: set_AlignScripts()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje zarovnání dolního/horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány vůči sobě. Když je false, jsou přizpůsobeny tvaru základu. Výchozí hodnota je false.
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) metoda


Určuje zarovnání dolního/horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány vůči sobě. Když je false, jsou přizpůsobeny tvaru základu. Výchozí hodnota je false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

* Třída [MathRightSubSuperscriptElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)