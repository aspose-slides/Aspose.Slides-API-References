---
title: CreateMathLimit()
second_title: Aspose.Slides برای C++ مرجع API
description: یک IMathLimit ایجاد می‌کند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) متد

ایجاد می‌کند [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | آرگومان پایه برای اعمال محدودیت |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر محدودیت |
| upperLimit | **bool** | موقعیت قرارگیری محدودیت را در بالا تنظیم می‌کند |

### مقدار بازگشت

محدودیت ریاضی جدید

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

ایجاد می‌کند [IMathLimit](../../imathlimit/) با محدودیت در پایین

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | آرگومان پایه برای اعمال محدودیت |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر محدودیت |

### مقدار بازگشت

محدودیت ریاضی جدید

## ارجاع‌های مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathLimit](../../imathlimit/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathLimitFactory](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)