---
title: get_AlignScripts()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Specifikuje zarovnání dolního a horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány k sobě. Když je false, jsou přizpůsobeny tvaru základny. Výchozí hodnota je false.
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metoda


Určuje zarovnání dolního a horního indexu. Když je true, dolní a horní index jsou vodorovně zarovnány k sobě. Když je false, jsou přizpůsobeny tvaru základny. Výchozí hodnota je false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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