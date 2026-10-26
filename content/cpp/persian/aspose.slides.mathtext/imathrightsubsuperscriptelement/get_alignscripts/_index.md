---
title: get_AlignScripts()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که زیرنویس/بالانویس چگونه تراز شوند. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر تراز می‌شوند. وقتی مقدار false باشد، آنها به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() متد

تعیین می‌کند که زیرنویس/بالانویس چگونه تراز شوند. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر تراز می‌شوند. وقتی مقدار false باشد، آنها به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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