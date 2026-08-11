---
title: set_AlignScripts()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يحدد محاذاة النص السفلي/العُلوي. عندما تكون القيمة true، يتم محاذاة النص السفلي والعلوي أفقيًا لبعضهما البعض. عندما تكون القيمة false، يتم تعديلهما لتناسب شكل القاعدة. القيمة الافتراضية هي false.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) طريقة


يحدد محاذاة النص السفلي/العلوي. عند القيمة true، يتم محاذاة النص السفلي والعلوي أفقيًا لبعضهما البعض. عند القيمة false، يتم تعديلهما لتناسب شكل القاعدة. القيمة الافتراضية هي false.

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

## انظر أيضاً

* فئة [MathRightSubSuperscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)