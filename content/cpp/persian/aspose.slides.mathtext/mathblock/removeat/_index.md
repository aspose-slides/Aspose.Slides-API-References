---
title: RemoveAt()
second_title: Aspose.Slides برای مرجع API C++
description: عنصری را که در اندیس مشخص شده از مجموعه قرار دارد حذف می‌کند.
type: docs
weight: 170
url: /fa/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) متد

عنصری را که در اندیس مشخص شده‌ی مجموعه قرار دارد حذف می‌کند.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-مبنای عنصری که باید حذف شود. |

## توضیحات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## موارد مرتبط

* کلاس [MathBlock](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)