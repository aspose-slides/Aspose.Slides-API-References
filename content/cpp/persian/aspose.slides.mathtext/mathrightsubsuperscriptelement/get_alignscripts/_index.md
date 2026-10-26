---
title: get_AlignScripts()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند که تنظیم زیرنویس/بالانویس چگونه باشد. زمانی که true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر هم‌راستا می‌شوند. زمانی که false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() متد

تعیین می‌کند که تنظیمات زیرنویس/بالانویس چگونه باشد. زمانی که true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر هم‌راستا می‌شوند. زمانی که false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

## همچنین ببینید

* کلاس [MathRightSubSuperscriptElement](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)