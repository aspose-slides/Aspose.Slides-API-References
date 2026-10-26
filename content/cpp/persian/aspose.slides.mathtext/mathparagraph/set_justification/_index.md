---
title: set_Justification()
second_title: Aspose.Slides برای C++ مرجع API
description: "Paragraph Justification مقدار پیش‌فرض: CenteredAsGroup"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) متد


[Paragraph](../../../aspose.slides/paragraph/) Justification مقدار پیش‌فرض: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## توضیحات


مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## موارد مرتبط

* Enum [MathJustification](../../mathjustification/)
* کلاس [MathParagraph](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)