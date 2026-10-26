---
title: set_SpellCheck()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد قيمة تشير إلى ما إذا كان تمكين التدقيق الإملائي مفعلاً لجزء النص. عندما يتم تعيين هذه الخاصية إلى false، يتم قمع فحوصات الإملاء لعناصر النص. عندما يتم تعيينها إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي false.
type: docs
weight: 612
url: /ar/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) طريقة

يحدد قيمة تشير إلى ما إذا كان تمكين التدقيق الإملائي مفعلاً لجزء النص. عندما يتم تعيين هذه الخاصية إلى false، يتم قمع فحوصات الإملاء لعناصر النص. عندما يتم تعيينها إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## ملاحظات

المثال التالي يوضح تمكين علم SpellCheck قبل حفظ العرض التقديمي: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
portion->get_PortionFormat()->set_SpellCheck(true);
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [BasePortionFormat](../)
* نطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)