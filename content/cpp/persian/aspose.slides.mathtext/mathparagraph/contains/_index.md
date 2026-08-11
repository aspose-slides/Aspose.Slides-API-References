---
title: Contains()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا مجموعه حاوی مقدار خاصی است یا خیر.
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) متد

تعیین می‌کند که آیا مجموعه حاوی مقدار خاصی است یا خیر.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | شیء‌ای که باید در مجموعه یافت شود. |

### مقدار بازگشتی

اگر *mathBlock* در مجموعه یافت شود true؛ در غیر این صورت false.

## توضیحات



مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [MathParagraph](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)