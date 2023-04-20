---
title: set_AlignScripts()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false.
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) method


Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Remarks


Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## See Also

* Class [MathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)