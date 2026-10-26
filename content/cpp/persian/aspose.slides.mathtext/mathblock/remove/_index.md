---
title: Remove()
second_title: راهنمای API Aspose.Slides برای C++
description: اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) متد

نخستین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | شیئی که باید از مجموعه حذف شود. |

### مقدار بازگشتی

true اگر *item* با موفقیت از مجموعه حذف شود؛ در غیر این صورت false. این متد همچنین false بر می‌گرداند اگر *item* در مجموعه اصلی یافت نشود.

## نکات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)