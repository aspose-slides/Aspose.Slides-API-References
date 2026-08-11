---
title: get_SpellCheck()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تشير إلى ما إذا كان تم تمكين التدقيق الإملائي للجزء النصي. عندما يتم تعيين هذه الخاصية إلى false، يتم كبح فحوصات الإملاء للعناصر النصية. عندما يتم تعيينها إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي false.
type: docs
weight: 599
url: /ar/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() طريقة

يحصل على قيمة تشير إلى ما إذا كان تم تمكين التدقيق الإملائي للجزء النصي. عندما يتم تعيين هذا الخاصية إلى false، يتم كبح فحوصات الإملاء للعناصر النصية. عندما يتم تعيينها إلى true، يُسمح بالتدقيق الإملائي. القيمة الافتراضية هي **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## ملاحظات

المثال التالي يوضح تمكين علم SpellCheck قبل حفظ العرض التقديمي:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// الوصول إلى الجزء النصي الأول داخل الشكل الأول على الشريحة الأولى
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// تمكين التدقيق الإملائي لهذا الجزء النصي
portion->get_PortionFormat()->set_SpellCheck(true);
// حفظ العرض التقديمي المعدل
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* صف [BasePortionFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)