---
title: HighlightRegex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُبرز جميع التطابقات للتعبير النمطي باستخدام اللون المحدد.
type: docs
weight: 469
url: /ar/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) طريقة

يُبرز جميع التطابقات للتعبير النمطي باستخدام اللون المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل التي سيتم تمييزها. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتحديد النص. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

يوضح المثال البرمجي التالي كيفية تمييز النص في عرض PowerPoint [Presentation](../../presentation/) باستخدام تعبير نمطي.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [Color](../../../system.drawing/color/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [IPresentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)