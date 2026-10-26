---
title: ToBorderBox()
second_title: مرجع API Aspose.Slides برای C++
description: این عنصر را در یک border-box قرار می‌دهد
type: docs
weight: 261
url: /fa/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() متد

این عنصر را در یک border-box قرار می‌دهد

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### مقدار بازگشت

border-box که این عنصر در داخل آن قرار گرفته است
## توضیحات

مثال:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) متد

این عنصر را در یک border-box قرار می‌دهد

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | پنهان کردن لبه بالا |
| hideBottom | **bool** | پنهان کردن لبه پایین |
| hideLeft | **bool** | پنهان کردن لبه چپ |
| hideRight | **bool** | پنهان کردن لبه راست |
| strikethroughHorizontal | **bool** | خط خورده افقی در Border Box |
| strikethroughVertical | **bool** | خط خورده عمودی در Border Box |
| strikethroughBottomLeftToTopRight | **bool** | خط خورده از پایین-چپ به بالا-راست در Border Box |
| strikethroughTopLeftToBottomRight | **bool** | خط خورده از بالا-چپ به پایین-راست در Border Box |

### مقدار بازگشت

border-box که این عنصر در داخل آن قرار گرفته است
## توضیحات

مثال:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBorderBox](../../imathborderbox/)
* کلاس [IMathElement](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)