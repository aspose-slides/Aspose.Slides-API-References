---
title: set_AlignScripts()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند تراز زیرنویس/بالانویس. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر تراز می‌شوند. وقتی مقدار false باشد، نسبت به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) متد

تعیین می‌کند نحوهٔ تراز زیرنویس/بالانویس. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر تراز می‌شوند. وقتی مقدار false باشد، نسبت به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## توضیحات

مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## موارد مرتبط

* کلاس [IMathRightSubSuperscriptElement](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)