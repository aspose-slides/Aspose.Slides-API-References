---
title: Clear()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام عناصر را از مجموعه حذف می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() متد

تمام عناصر را از مجموعه حذف می‌کند.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## توضیحات

مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## موارد مرتبط

* کلاس [MathParagraph](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)