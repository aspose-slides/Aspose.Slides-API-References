---
title: idx_set()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر ماتریس
type: docs
weight: 222
url: /fa/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) متد

عنصر ماتریس

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| row | **int32_t** | شاخص صفر-مبنا برای row جهت دریافت آیتم |
| column | **int32_t** | شاخص صفر-مبنا برای column جهت دریافت آیتم |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)