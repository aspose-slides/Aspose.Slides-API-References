---
title: set_AlignScripts()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند که چیدمان زیرنویس/بالانویس چگونه باشد. وقتی true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر هم‌تراز می‌شوند. وقتی false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) متد

تعیین می‌کند که چیدمان زیرنویس/بالانویس چگونه باشد. وقتی true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر هم‌تراز می‌شوند. وقتی false باشد، بر شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## ملاحظات

مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## همچنین

* کلاس [MathRightSubSuperscriptElement](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)