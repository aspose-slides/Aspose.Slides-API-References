---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false.
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() method


Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

* Class [IMathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)