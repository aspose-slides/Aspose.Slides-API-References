---
title: get_AlignScripts()
second_title: Aspose.Slides للمرجع البرمجي C++
description: يحدد محاذاة النص السفلي/النص العلوي. عندما تكون true، يتم محاذاة النص السفلي والنص العلوي أفقياً معًا. عندما تكون false، يتم تعديل التباعد ليتناسب مع شكل الأساس. القيمة الافتراضية هي false.
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() طريقة

يحدد محاذاة النص السفلي/النص العلوي. عندما تكون true، يتم محاذاة النص السفلي والنص العلوي أفقياً معًا. عندما تكون false، يتم فك المسافة لتتناسب مع شكل الأساس. القيمة الافتراضية هي false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

## انظر أيضا

* فئة [MathRightSubSuperscriptElement](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)