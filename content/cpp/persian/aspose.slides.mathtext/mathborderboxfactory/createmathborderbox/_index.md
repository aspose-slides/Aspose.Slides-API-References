---
title: CreateMathBorderBox()
second_title: Aspose.Slides برای C++ مرجع API
description: یک جعبه مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) متد

یک جعبه مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال جعبه مرزی |

### مقدار بازگشت

عنصر جدید جعبه مرزی

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) متد

یک جعبه مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال جعبه مرزی |
| hideTop | **bool** | پنهان کردن لبه بالایی |
| hideBottom | **bool** | پنهان کردن لبه پایینی |
| hideLeft | **bool** | پنهان کردن لبه چپ |
| hideRight | **bool** | پنهان کردن لبه راست |
| strikethroughHorizontal | **bool** | خط‌خورده افقی جعبه مرزی |
| strikethroughVertical | **bool** | خط‌خورده عمودی جعبه مرزی |
| strikethroughBottomLeftToTopRight | **bool** | خط‌خورده از پایین-چپ به بالا-راست جعبه مرزی |
| strikethroughTopLeftToBottomRight | **bool** | خط‌خورده از بالا-چپ به پایین-راست جعبه مرزی |

### مقدار بازگشت

عنصر جدید جعبه مرزی

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBorderBox](../../imathborderbox/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBorderBoxFactory](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)