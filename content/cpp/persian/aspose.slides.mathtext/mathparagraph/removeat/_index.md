---
title: RemoveAt()
second_title: مرجع API Aspose.Slides برای C++
description: یک مورد را در ایندکس مشخص‌شده از مجموعه حذف می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) متد

یک مورد را در ایندکس مشخص‌شده از مجموعه حذف می‌کند.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-مبنا برای حذف مورد. |
## نکات

مثال:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## مراجع

* کلاس [MathParagraph](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)