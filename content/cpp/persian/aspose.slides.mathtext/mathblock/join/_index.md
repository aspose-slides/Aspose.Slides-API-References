---
title: Join()
second_title: مرجع API Aspose.Slides برای C++
description: یک عنصر ریاضی را به این بلوک ریاضی می‌پیوندد
type: docs
weight: 183
url: /fa/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) متد

یک عنصر ریاضی را به این بلوک ریاضی می‌پیوندد

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصری که باید به‌هم پیوست شود |

### مقدار بازگشتی

نمونهٔ فعلی [IMathBlock](../../imathblock/)

## توضیحات


مثال:
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) متد

یک متن ریاضی را به این بلوک ریاضی می‌پیوندد

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | متن ریاضی که باید به‌هم پیوست شود |

### مقدار بازگشتی

یک [IMathBlock](../../imathblock/) جدید که این نمونه و آرگومان مشخص شده را شامل می‌شود

## توضیحات


مثال:
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBlock](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)