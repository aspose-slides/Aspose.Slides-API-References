---
title: ToBorderBox()
second_title: مرجع API برای Aspose.Slides برای C++
description: این عنصر را در یک جعبه‌مرزی قرار می‌دهد
type: docs
weight: 248
url: /fa/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() متد

این عنصر را در یک جعبه‌مرزی قرار می‌دهد

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### مقدار بازگشت

جعبه‌مرزی با این عنصر داخل آن

## توضیحات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) متد

این عنصر را در یک جعبه‌مرزی قرار می‌دهد

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hideTop | **bool** | پنهان کردن لبه بالایی |
| hideBottom | **bool** | پنهان کردن لبه پایینی |
| hideLeft | **bool** | پنهان کردن لبه چپ |
| hideRight | **bool** | پنهان کردن لبه راست |
| strikethroughHorizontal | **bool** | قلم‌خط افقی جعبه‌مرزی |
| strikethroughVertical | **bool** | قلم‌خط عمودی جعبه‌مرزی |
| strikethroughBottomLeftToTopRight | **bool** | قلم‌خط جعبه‌مرزی از گوشه پایین چپ به سمت بالا راست |
| strikethroughTopLeftToBottomRight | **bool** | قلم‌خط جعبه‌مرزی از گوشه بالا چپ به سمت پایین راست |

### مقدار بازگشت

جعبه‌مرزی با این عنصر داخل آن

## توضیحات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBorderBox](../../imathborderbox/)
* کلاس [MathElementBase](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)