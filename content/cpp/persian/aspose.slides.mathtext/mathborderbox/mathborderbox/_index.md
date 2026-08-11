---
title: MathBorderBox()
second_title: مرجع API Aspose.Slides برای C++
description: عنصری از نوع MathBorderBox با حاشیه مستطیلی ایجاد می‌کند
type: docs
weight: 222
url: /fa/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) سازنده


عنصری از نوع [MathBorderBox](../) با حاشیه مستطیلی ایجاد می‌کند

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Arguments

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر پایه‌ای که جعبه مرزی به آن اعمال می‌شود. می‌تواند مقدار null باشد. |
## توضیحات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) سازنده


عنصری از نوع [MathBorderBox](../) ایجاد می‌کند

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Arguments

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر پایه‌ای که جعبه مرزی به آن اعمال می‌شود |
| hideTop | **bool** | پنهان کردن لبه بالایی |
| hideBottom | **bool** | پنهان کردن لبه پایینی |
| hideLeft | **bool** | پنهان کردن لبه چپ |
| hideRight | **bool** | پنهان کردن لبه راست |
| strikethroughHorizontal | **bool** | خط‌کش افقی |
| strikethroughVertical | **bool**. | خط‌کش عمودی |
| strikethroughBottomLeftToTopRight | **bool** | خط‌کش از سمت پایین‌چپ به بالا‌راست |
| strikethroughTopLeftToBottomRight | **bool** | خط‌کش از سمت بالا‌چپ به پایین‌راست |
## توضیحات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBorderBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)