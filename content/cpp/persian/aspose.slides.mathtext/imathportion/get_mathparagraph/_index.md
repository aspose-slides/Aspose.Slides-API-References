---
title: get_MathParagraph()
second_title: Aspose.Slides برای C++ مرجع API
description: پاراگراف ریاضی
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathportion/get_mathparagraph/
---
## IMathPortion::get_MathParagraph() متد


پاراگراف ریاضی

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathPortion::get_MathParagraph()=0
```

## توضیحات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathParagraph](../../imathparagraph/)
* کلاس [IMathPortion](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)