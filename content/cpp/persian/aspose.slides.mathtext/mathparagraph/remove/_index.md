---
title: Remove()
second_title: مرجع API Aspose.Slides برای C++
description: اولین رخداد یک شی خاص را از مجموعه حذف می‌کند/>
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) متد

اولین رخداد یک شی‌ای که باید از مجموعه/> حذف شود.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | شی‌ای که باید از مجموعه حذف شود. |

### مقدار بازگشتی

true اگر *mathBlock* با موفقیت از مجموعه حذف شده باشد؛ در غیر این صورت false. این متد همچنین در صورتی که *mathBlock* در مجموعه اصلی پیدا نشود false باز می‌گرداند/>.

## توضیحات

مثال:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [MathParagraph](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)