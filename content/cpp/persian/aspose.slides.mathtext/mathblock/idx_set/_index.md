---
title: idx_set()
second_title: Aspose.Slides برای مرجع API C++
description: عنصر IMathElement را در اندیس مشخص تنظیم می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) متد

[IMathElement](../../imathelement/) را در ایندکس مشخص تنظیم می‌کند.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنا برای آیتم |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی. |

## ملاحظات

مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBlock](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)