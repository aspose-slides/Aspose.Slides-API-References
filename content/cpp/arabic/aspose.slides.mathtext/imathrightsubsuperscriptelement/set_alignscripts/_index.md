---
title: set_AlignScripts()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد محاذاة النص السفلي/العُلوي. عندما تكون true، يتم محاذاة النص السفلي والنص العُلوي أفقياً بالنسبة لبعضهما البعض. عندما تكون false، يتم مقاربتها إلى شكل القاعدة. القيمة الافتراضية هي false.
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) طريقة

يحدد محاذاة النص السفلي/العُلوي. عندما تكون true، يتم محاذاة النص السفلي والنص العُلوي أفقياً بالنسبة لبعضهما البعض. عندما تكون false، يتم مقَرّب إلى شكل القاعدة. القيمة الافتراضية هي false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)