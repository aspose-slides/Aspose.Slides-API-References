---
title: get_Justification()
second_title: Aspose.Slides برای مرجع API C++
description: "Paragraph Justification مقدار پیش‌فرض: CenteredAsGroup"
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() متد

[Paragraph](../../../aspose.slides/paragraph/) تراز مقدار پیش‌فرض: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## توضیحات

مثال:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## مراجع

* شمارش [MathJustification](../../mathjustification/)
* کلاس [IMathParagraph](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)