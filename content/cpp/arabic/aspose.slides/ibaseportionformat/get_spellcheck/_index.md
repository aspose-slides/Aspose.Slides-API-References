---
title: get_SpellCheck()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على قيمة تشير إلى ما إذا كان تدقيق الإملاء مفعلاً للجزء النصي. عندما تُضبط هذه الخاصية على false، يتم كبح عمليات تدقيق الإملاء لعناصر النص. عندما تُضبط على true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي false.
type: docs
weight: 599
url: /ar/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() طريقة

يحصل على قيمة تشير إلى ما إذا كان تمكين تدقيق الإملاء مفعلاً للجزء النصي. عندما تُضبط هذه الخاصية على false، يتم كبح عمليات تدقيق الإملاء لعناصر النص. عندما تُضبط على true، يُسمح بتدقيق الإملاء. القيمة الافتراضية هي **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## ملاحظات

المثال التالي يوضح تمكين علم SpellCheck قبل حفظ العرض التقديمي: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx"); // الوصول إلى الجزء الأول من النص داخل الشكل الأول في الشريحة الأولى
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0); // تمكين تدقيق الإملاء لهذا الجزء النصي
portion->get_PortionFormat()->set_SpellCheck(true); // حفظ العرض التقديمي المعدل
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [IBasePortionFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)