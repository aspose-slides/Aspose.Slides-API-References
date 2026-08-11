---
title: CreateMathBorderBox()
second_title: Aspose.Slides برای C++ مرجع API
description: یک جعبه‌حاشیه ریاضی با اعمال به عنصر ایجاد می‌کند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) متد


یک جعبه‌حاشیه ریاضی با اعمال به عنصر ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال جعبه‌حاشیه |

### مقدار بازگشت

عنصر جعبهٔ حاشیهٔ جدید

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) متد


یک جعبه‌حاشیه ریاضی با اعمال به عنصر ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال جعبه‌حاشیه |
| hideTop | **bool** | مخفی‌سازی لبهٔ بالا |
| hideBottom | **bool** | مخفی‌سازی لبهٔ پایین |
| hideLeft | **bool** | مخفی‌سازی لبهٔ چپ |
| hideRight | **bool** | مخفی‌سازی لبهٔ راست |
| strikethroughHorizontal | **bool** | خط‌کش افقی جعبه‌حاشیه |
| strikethroughVertical | **bool** | خط‌کش عمودی جعبه‌حاشیه |
| strikethroughBottomLeftToTopRight | **bool** | خط‌کش از پایین-چپ به بالا-راست جعبه‌حاشیه |
| strikethroughTopLeftToBottomRight | **bool** | خط‌کش از بالا-چپ به پایین-راست جعبه‌حاشیه |

### مقدار بازگشت

عنصر جعبهٔ حاشیهٔ جدید

## مرجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBorderBox](../../imathborderbox/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathBorderBoxFactory](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)