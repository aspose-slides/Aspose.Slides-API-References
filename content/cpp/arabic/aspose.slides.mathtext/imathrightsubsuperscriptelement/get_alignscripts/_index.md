---
title: get_AlignScripts()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد محاذاة النص السفلي/النص العلوي. عندما يكون true، يتم محاذاة النص السفلي والعلوي أفقياً بالنسبة لبعضهما. عندما يكون false، يتم إقرابهما إلى شكل العنصر الأساسي. القيمة الافتراضية هي false.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() طريقة


يحدد محاذاة النص السفلي/النص العلوي. عندما يكون true، يتم محاذاة النص السفلي والعلوي أفقياً بالنسبة لبعضهما. عندما يكون false، يتم إقرابهما إلى شكل العنصر الأساسي. القيمة الافتراضية هي false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

## انظر أيضًا

* فئة [IMathRightSubSuperscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)