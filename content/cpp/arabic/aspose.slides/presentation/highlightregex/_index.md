---
title: HighlightRegex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُبرز جميع التطابقات للتعبير النمطي باللون المحدد.
type: docs
weight: 508
url: /ar/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) طريقة

يُبرز جميع مطابقات التعبير النمطي باللون المحدد.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل لتتمييزها. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتتمييز النص. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات

يعرض المثال البرمجي التالي كيفية تمييز النص في ملف PowerPoint [Presentation](../) باستخدام تعبير نمطي.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// تمييز جميع الكلمات التي تتكون من 10 أحرف أو أكثر
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [Color](../../../system.drawing/color/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [Presentation](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)