---
title: set_SpellCheck()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط قيمة تُشير إلى ما إذا كان تمكين التدقيق الإملائي للجزء النصي. عندما تُضبط هذه الخاصية على false، يتم كبح فحوصات الإملاء لعناصر النص. عندما تُضبط على true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي false.
type: docs
weight: 612
url: /ar/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) طريقة

يضبط قيمة تشير إلى ما إذا كان تمكين التدقيق الإملائي للجزء النصي. عندما يتم تعيين هذه الخاصية إلى false، يتم قمع فحص الإملاء لعناصر النص. عندما يتم تعيينها إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
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

* الفئة [IBasePortionFormat](../)
* نطاق الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)