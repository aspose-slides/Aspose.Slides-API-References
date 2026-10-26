---
title: get_MathParagraph()
second_title: Aspose.Slides لمرجع API للـ C++
description: فقرة رياضية
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathportion/get_mathparagraph/
---
## IMathPortion::get_MathParagraph() طريقة


فقرة رياضية

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathPortion::get_MathParagraph()=0
```

## ملاحظات


مثال:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathParagraph](../../imathparagraph/)
* فئة [IMathPortion](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)