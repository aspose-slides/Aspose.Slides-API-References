---
title: get_MathParagraph()
second_title: Aspose.Slides for C++ API Reference
description: Math paragraph
type: docs
weight: 1
url: /aspose.slides.mathtext/imathportion/get_mathparagraph/
---
## IMathPortion::get_MathParagraph() method


Math paragraph

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathPortion::get_MathParagraph()=0
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<Aspose::Slides::MathText::MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathParagraph](../../imathparagraph/)
* Class [IMathPortion](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)