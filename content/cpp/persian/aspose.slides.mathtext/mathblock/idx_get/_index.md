---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: المان IMathElement را در اندیس مشخص شده دریافت می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) متد


دریافت [IMathElement](../../imathelement/) در اندیس مشخص شده.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایهٔ آیتم |

### مقدار بازگشتی

عنصر ریاضی.

## توضیحات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBlock](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)